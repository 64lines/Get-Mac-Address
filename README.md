Get-Mac-Address
===============


    public String macAddress()
    {
    	WifiManager wifiManager = (WifiManager) getSystemService(Context.WIFI_SERVICE);
    	WifiInfo wInfo = wifiManager.getConnectionInfo();
    	return wInfo.getMacAddress(); 
    }

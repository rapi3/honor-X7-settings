# Honor-X7-settings
Settings from Honor X7a phone accessed from adb:<br>
./adb shell<br>

settings list global<br>
settings list secure<br>
settings list system<br>

# You can read and change any seetings.
For example to stop uploading data to Honor analytics server:<br>
https://metrics-dre.dt.hihonorcloud.com:443<br>

settings get global com.hihonor.android.pushagent.analytics_server_url<br>
settings put global com.hihonor.android.pushagent.analytics_server_url "https://127.0.0.1:443"<br>

settings get global com.hihonor.android.pushagent.grs_zone_id<br>
settings put global com.hihonor.android.pushagent.grs_zone_id ""<br>

settings get global wifi_hidata_rtt_url<br>
settings put global wifi_hidata_rtt_url "connectivitycheck.gstatic.com|www.google.com"<br>

settings get global hicall_support_countries<br>
settings put global hicall_support_countries UK<br>

settings get global supl_server_cn<br>
settings put global supl_server_cn ""<br>

settings get secure push_white_apps<br>
settings put secure push_white_apps ""<br>

settings get secure privacy_app_blacklist<br>
settings put secure privacy_app_blacklist ""<br>

settings get secure location_honor_ads<br>
settings put secure location_honor_ads=0<br>

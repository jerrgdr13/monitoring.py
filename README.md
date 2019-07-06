# monitoring.py
#This is for monitoring purposes.

#$language = "Python"
#$interface = "1.0"

import webbrowser
import time

monitoringtool = [

	# Pre-tasks
	"http://URL",
	"http://URL",
	
]
#After the login on the SIDE2 actions processed the Script will open the below Links related to the loged application.
splunk = [

	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	"http://URL",
	
]

#After the login actions processed the Script will open the below Links related to the loged application.
introTool = [

	"http://URL",
	"http://URL",
	
]

print("************************************")
print("***    Opening ApplicationName   ***")
print("************************************")
print("Please authenticate into Monitoring with your user and password.")
#Below you will be requested for the first loging on the SIDE1
webbrowser.open_new("https://loging Page")
input("After you get authenticated, please press a key to continue...")

for url in general:
	webbrowser.open_new(url)
	time.sleep(1)

print("******************************")
print("***     Opening Splunk     ***")
print("******************************")
print("Please authenticate into Splunk with your user and password.")
#After the login actions processed the Script will open the below Links related to the loged application this are SIDE2.
webbrowser.open_new("https://SplunkLogingpage/")
input("After you get authenticated, please press a key to continue...")

for url in splunk:
	webbrowser.open_new(url)
	time.sleep(15)

print("********************************")
print("***   Opening Monitoring Tool***")
print("********************************")
print("The first monitoring tool dashboards are opened just to get authenticated automatically from other tool.")
print("You can close them after this script finishes.")

# Pre-authentication for Introscope Dashboards
webbrowser.open_new("Authentication page for the monitoring tool")
webbrowser.open_new("Authentication page for the monitoring tool")

for url in introTool:
	webbrowser.open_new(url)
	time.sleep(15)

print("******************************")
print("*** Opening Other tools ***")
print("******************************")
webbrowser.open_new("http://toolsLogingPage")


print("Finished!")

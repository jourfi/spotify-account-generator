# spotify-account-generator
This Python3 script instantly generates new free Spotify accounts (with random credentials) while pretending to be a Spotify app (currently v8.6.26) installed on an Android device. This is simply achieved by sending forged HTTP requests. The original requests have been intercepted from an emulator of a SM-N976N device running Android Lollipop, that is why you will find this particular model in the "User-Agent" header of the requests.

Note: I won't test this script often, so if Spotify will change their API specifications this script may not work until updated.
DISCLAIMER: by using any of the files available in this repository, you understand that you are agreeing to use at your own risk. All files available here are for education and/or research only.

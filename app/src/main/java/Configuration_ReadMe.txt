//keytool -exportcert \ -alias <your-key-name> \ -keystore <path-to-production-keystore> \ -list -v
//keytool -exportcert \ -alias androiddebugkey \ -keystore <path-to-debug-keystore> \ -list -v

1. keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android

Alias name: androiddebugkey
Creation date: 07 Oct 2015
Entry type: PrivateKeyEntry
Certificate chain length: 1
Certificate[1]:
Owner: CN=Android Debug, O=Android, C=US
Issuer: CN=Android Debug, O=Android, C=US
Serial number: 74eb41a9
Valid from: Wed Oct 07 10:22:15 SAST 2015 until: Fri Sep 29 10:22:15 SAST 2045
Certificate fingerprints:
	 MD5:  B9:0D:7B:33:A4:D3:47:4A:46:6A:9B:03:93:26:14:9B
	 SHA1: ED:72:3A:E3:75:48:F9:65:E5:2B:4B:99:B2:DE:F6:91:76:63:6D:68
	 SHA256: CE:72:1E:31:C7:67:FC:90:C5:B3:5C:B0:4B:C1:73:3A:21:56:4F:2A:D2:A3:5B:01:6E:DE:7F:E0:9E:9B:92:96
	 Signature algorithm name: SHA256withRSA
	 Version: 3

2. keytool -list -v -keystore /Users/KaraboMon/Downloads/BooGoogleSignIn/MyKeyStore.keystore -alias androiddebugkey -storepass android -keypass android

3. Google Cloud Messaging
Sender Id: 343798831435
Server API Key: AIzaSyCbChExF1A_xID09BWLqXa0utztoCquXZE

4. For the backend hereof, the server should have an OAuth 2.0 Client ID

5. Google Developer Console - Backend
Client ID: 116034280837-hpo9vdk96bg9eb6k3tifpt1co58ijo18.apps.googleusercontent.com
Client Secret: 0w4XmX7cZzmYq9HIYNr_ajhB

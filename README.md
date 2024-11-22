To combat dynamically loaded code in anti-emulated environments, DLCDroid is an Android app analysis framework. DLCDroid uses the reflection API to effectively identify information leaks
due to dynamically loaded code within malicious apps, incorporating static and dynamic analysis techniques. The Dynamically Loaded Code (DLC) technique employs Java features to allow 
Android apps to dynamically expand their functionality at runtime. Unfortunately, malicious app developers often exploit DLC techniques to transform seemingly benign apps into malware
once installed on real devices. Even the most sophisticated static analysis tools struggle to detect data breaches caused by DLC. Our analysis demonstrates that conventional tools 
are ill-equipped to handle DLC. DLCDroid leverages dynamic code interposition techniques for API hooking to expose concealed malicious behaviour without requiring modifications to the
Android framework. DLCDroid can unveil suspicious behaviour that remains hidden when relying solely on static analysis. We evaluate DLCDroid’s performance using a dataset comprising real-world benign and malware apps from reputed repositories like VirusShare and the Google Play Store.

Please access our dataset using the Google Drive URL with prior permission.
https://drive.google.com/drive/folders/1t0wd46S5sxb1JzvuMgdRLIEqH8Tph4_6?usp=share_link



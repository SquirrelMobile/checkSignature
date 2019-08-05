# pdfView for Android

Module for getting certificate fingerprint from android app

## Module Naming

    fr.squirrel.checksignature

## Example usage

The method "getCertificateSHA1Fingerprint" get the fingerprint SHA1
Example index.js :

```


    var certificate = require("fr.squirrel.checksignature").getCertificateSHA1Fingerprint();
		if (certificate !== Alloy.CFG.certificateSHA1) {
			Alloy.Globals.toast(L("pair.error.title"));
			var activity = Titanium.Android.currentActivity;
			if (activity) {
				activity.finish();
			}
			return false;
		}

```

## Methods

- getCertificateSHA1Fingerprint() : this method return the current Fingerprint SHA1

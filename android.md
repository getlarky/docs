---
layout: page
title: "Android"
date:   2016-02-12 11:56:42

permalink: /android/

# categories: 
---

## Getting Started

Larky for Android makes it easy to add location-based notifications and valuable perk data to your native Android app.  Getting started is as easy as adding `larky-{version}.jar` to your `libs` folder and initializing a singleton which can be used throughout your application:  

```
Larky larky = new Larky.LarkyBuilder(YOUR_LARKY_API_KEY).build();
Larky.initialize(larky);

larky.larky().getPerks(...);
```

Result:  

``` json
{
	"perks":[
	{
		"id":7048,
		"merchant_id":31,
		"perk_type_id":",3,57,",
		"organization_id":222,
		"member_level_id":1,
		"description":"Get 10% off produce every Wednesday.",
		"expiry_date":null,
		"is_fav":false,
		"is_new":false,
		"organization_name":"Blue Cross Blue Shield of Michigan - Healthy Blue Xtras",
		"redeem":null
	},
	{
		"id":7021,
		"merchant_id":32,
		"perk_type_id":",14,56,",
		"organization_id":222,
		"member_level_id":1,
		"description":"15% off total order. ",
		"expiry_date":null,
		"is_fav":false,
		"is_new":false,
		"organization_name":"Blue Cross Blue Shield of Michigan - Healthy Blue Xtras",
		"redeem":null
	}],
	"is_last":false
}
```

### Permissions

The Larky library requires the following permissions to be present in your AndroidManifest.xml file:  

```
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.ACCESS_MOCK_LOCATION" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.GET_ACCOUNTS" />
```

Larky supports API 12 and above.  

---

## Notifications

## Organizations

## Users

## Account Federation

## Memberships

## Categories

## Merchants

## Perks

## Redemption

## Affiliations

## Miscellaneous

---

## FAQ

#### Swine spare ribs chicken, leberkas doner turkey jowl sirloin ribeye?

Tongue pig shoulder flank. Sirloin picanha andouille corned beef, jerky flank kielbasa boudin meatloaf capicola swine pork chop. 

#### Biltong tongue leberkas ham ground round short loin?

Beef ribs tri-tip ribeye andouille tongue chicken landjaeger. Sirloin sausage meatball, tongue brisket pork belly picanha.

## Troubleshooting

Turkey rump pig pancetta cupim ham salami ball tip brisket porchetta pork chop short loin drumstick cow. 

#### Capicola pastrami pancetta, short ribs rump pork loin leberkas tongue?

* meatloaf
* shank
* chuck
* tenderloin
* pig
* porchetta
* pork chop
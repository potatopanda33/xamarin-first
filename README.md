# Sample Deprecated & Replaced

This sample has officially been deprecated and replaced with the "[My Contacts](https://github.com/xamarin/app-contacts)" sample application that showcases Xamarin.Forms and an ASP.NET Core backend.

This repo is left here for historical purposes, back links, and is read-only.

# app-customers
<img src="https://raw.githubusercontent.com/xamarin/app-customers/master/Screenshots/Customers_Screens.jpg" />

A simple Xamarin.Forms demo app with three primary screens:

* a list screen
* a read-only detail screen
* an editable detail screen

Includes integrations such as:

* getting directions
* making calls
* sending text messages
* email composition

##Build Status
[![Build Status](https://www.bitrise.io/app/7210fb7015b6b6b6.svg?token=y5K_xmtDXKdEzUprMqbWTg&branch=master)](https://www.bitrise.io/app/7210fb7015b6b6b6)

## Google Maps API key (Android)
For Android, you'll need to obtain a Google Maps API key:
https://developer.xamarin.com/guides/android/platform_features/maps_and_location/maps/obtaining_a_google_maps_api_key/

Insert it in `~/Droid/Properties/AndroidManifest.xml`:

    <application android:label="Customers" android:theme="@style/CustomersTheme">\
      ...
      <meta-data android:name="com.google.android.geo.API_KEY" android:value="[YOUR API KEY HERE]" />
      ...
    </application>

# SharePreferences
============
```
Easy way to put and get data and Object for the shared preferences in Android and easy to use.

Preferences preferences;

preferences = new Preferences(this);


//put String

preferences.putString("key", "value");

//get String

String name = preferences.getString("key");

//clear preference;

 preferences.clear();
 
 //remove key and value
 
 preferences.remove("key");
```

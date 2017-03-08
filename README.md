# SharePreferences
Easy way to put and get data and Object for the shared preferences in Android and easy to use.

Preferences preferences;

pref = new Preferences(this);


//put String
pref.putString("key", "value");

//get String
String name = pref.getString("key");

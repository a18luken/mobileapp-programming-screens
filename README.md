
# Rapport
La till loggar för aktivitetens livscykel i felsökningssyfte
Lade till en ny aktivitet för nästa layout, detta hade nog med fördel gjorts sist, men vid tillfället det gjordes verkade det logiskt att börja bygga biten jag skulle lägga till innan den lades till

Övergången till nästa aktivitet görs med följande kod
```
 public void onClick(View view) {
                Log.d("==>", "Sign in Button was clicked");
                Intent intent = new Intent(MainActivity.this, ProfileActivity.class);
                startActivity(intent);
```
En log lades till ifall något skulle gå fel så att jag enkelt kunde se om knappen reagerade.
När knappen klickas så startas en intent till ProfileActivity och följt av att den activiteten startas

Bilder läggs i samma mapp som markdown-filen.

![](android.png)

Kunde inte få den virtuella devicen att fungera på min hemmadator, därför finns ingen screenshot
# Acc
Prueba
     <intent-filter>
         <action android:name="android.intent.action.VIEW" />
         <category android:name="android.intent.category.DEFAULT" />
         <category android:name="android.intent.category.BROWSABLE" />
         <data
             android:scheme="https"
             android:host="tu-dominio.com"
             android:pathPrefix="/ruta" />
     </intent-filter>
     

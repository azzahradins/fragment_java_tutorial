# Tutorial Fragment Android Using Java
## Pendahuluan 

Fragment adalah potongan-potongan dari tampilan yang dapat dapat digunakan berulang-ulang kali pada satu activity maupun activity lain.

Pada penggunaan satu layout aplikasi kita dapat menyatukan beberapa fragment sehingga menjadi tampilan layout multi-pane.

Berikut merupakan contoh tampilan menggunakan fragment multi-pane :
![image1.png](image1.png)

<hr>

## Langkah dan Cara Menerapkan Fragment

<b>A. Mengkonfigurasi Bottom Navigation Bar </b>

1. Siapkan Android Studio anda.
2. Buatlah projek baru
3. Buatlah activity baru dengan layout "Bottom Navigation View"
4. Untuk memodifikasi nama bottom navigation kita dapat melakukan perubahan pada file `menu/bottom_nav_menu.xml`
5. Ubahlah file `menu/bottom_nav_menu.xml` seperti dibawah ini :
```xml
<menu xmlns:android="http://schemas.android.com/apk/res/android">
    <item
        android:id="@+id/navigation_home"
        android:icon="@drawable/ic_home_black_24dp"
        android:title="Welcome" />
    <item
        android:id="@+id/navigation_dashboard"
        android:icon="@drawable/ic_dashboard_black_24dp"
        android:title="Home" />
    <item
        android:id="@+id/navigation_notifications"
        android:icon="@drawable/ic_notifications_black_24dp"
        android:title="@string/title_notifications" />
</menu>
```
Penjelasan : pada file tersebut kita juga dapat mengatur id setiap bottom navigation dan icon pada bottom navigation bar tersebut.

6. Berikut hasil modified bottom navigation bar yang sudah kita buat :
![](image2.png)
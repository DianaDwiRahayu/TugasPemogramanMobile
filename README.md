# UTS Pemograman Mobile
# Nama : Diana Dwi Rahayu
# NIM : 312010055
# Kelas : TI.20.D.1

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="@drawable/login"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        app:cardCornerRadius="30dp"
        app:cardElevation="20dp"
        android:background="@drawable/pilihanku_edittext">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_gravity="center_horizontal"
            android:padding="24dp">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Login"
                android:id="@+id/LoginText"
                android:textSize="36sp"
                android:textAlignment="center"
                android:textStyle="bold"
                android:textColor="@color/black"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/Username"
                android:background="@drawable/pilihanku_edittext"
                android:drawableLeft="@drawable/baseline_person_24"
                android:drawablePadding="8dp"
                android:hint="Username"
                android:padding="8dp"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_margin="20dp"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/password"
                android:background="@drawable/pilihanku_edittext"
                android:drawableLeft="@drawable/baseline_lock_24"
                android:drawablePadding="8dp"
                android:hint="Password"
                android:padding="8dp"
                android:inputType="textPassword"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_margin="20dp"/>

            <Button
                android:layout_width="match_parent"
                android:layout_height="60dp"
                android:id="@+id/LoginButton"
                android:text="Login"
                android:textSize="18sp"
                android:layout_marginTop="30dp"
                android:backgroundTint="@color/blue"
                app:cornerRadius = "20dp"/>

        </LinearLayout>

    </androidx.cardview.widget.CardView>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="8dp"
        android:text="Not yet registered ? Sign Up Now"
        android:textSize="14sp"
        android:textAlignment="center"
        android:id="@+id/SignUpText"
        android:textColor="@color/blue"
        android:layout_marginBottom="20dp"/>

</LinearLayout>

<img width="723" alt="1" src="https://github.com/DianaDwiRahayu/TugasPemogramanMobile/assets/101866805/f625ded6-705f-4c8f-abbe-cccab2b80e98">

<p>
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="@drawable/beranda"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        app:cardCornerRadius="30dp"
        app:cardElevation="20dp"
        android:background="@drawable/pilihanku_edittext">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_gravity="center_horizontal"
            android:padding="4dp">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="PENDAFTARAN"
                android:id="@+id/LoginText"
                android:textSize="36sp"
                android:textAlignment="center"
                android:textStyle="bold"
                android:textColor="@color/black"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/Nama"
                android:background="@drawable/pilihanku_edittext"
                android:hint="Nama"
                android:padding="8dp"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_margin="20dp"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/email"
                android:background="@drawable/pilihanku_edittext"
                android:hint="Email"
                android:padding="8dp"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_margin="20dp"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/password"
                android:background="@drawable/pilihanku_edittext"
                android:hint="Password"
                android:padding="8dp"
                android:inputType="textPassword"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_margin="20dp"/>

            <Button
                android:layout_width="match_parent"
                android:layout_height="60dp"
                android:id="@+id/LoginButton"
                android:text="Sign Up"
                android:textSize="18sp"
                android:layout_marginTop="30dp"
                android:backgroundTint="@color/blue"
                app:cornerRadius = "20dp"/>

        </LinearLayout>

    </androidx.cardview.widget.CardView>

</LinearLayout>
  
<img width="721" alt="2" src="https://github.com/DianaDwiRahayu/TugasPemogramanMobile/assets/101866805/5f3f831a-280a-4cad-b2eb-5f4f550a9a9a">
 
 <p>
 <p> <?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/beranda"
    tools:context=".GridViewActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="40dp"
        android:id="@+id/title"
        android:text="PPDB ONLINE SKADA"
        android:textColor="@color/white"
        android:textSize="25sp"
        android:textAlignment="center"
        android:textStyle="bold"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:padding="140dp"
        android:text="Menu"
        android:id="@+id/LoginText"
        android:textSize="36sp"
        android:textAlignment="center"
        android:textStyle="bold"
        android:textColor="@color/black"/>

        <GridLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:id="@+id/gridLayout"
            android:rowCount="3"
            android:columnCount="2"
            android:layout_marginStart="80dp"
            android:layout_marginTop="280dp"
            android:layout_marginBottom="80dp">

            <androidx.cardview.widget.CardView
                android:id="@+id/imageCard"
                android:layout_width="115dp"
                android:layout_height="90dp"
                android:layout_row="0"
                android:layout_column="0"
                android:layout_margin="8dp"
                app:cardCornerRadius="20dp"
                android:elevation="10dp">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:gravity="center"
                    android:background="#03989E"
                    android:layout_gravity="center_vertical|center_horizontal">

                    <ImageView
                        android:layout_width="115dp"
                        android:layout_height="65dp"
                        android:src="@drawable/karate"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Seni Karate"
                        android:textColor="@color/white"
                        android:padding="3dp"
                        android:textAlignment="center"
                        android:textStyle="bold"/>
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:id="@+id/imageCard"
                android:layout_width="115dp"
                android:layout_height="90dp"
                android:layout_row="0"
                android:layout_column="1"
                android:layout_margin="8dp"
                app:cardCornerRadius="20dp"
                android:elevation="10dp">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:gravity="center"
                    android:background="#03989E"
                    android:layout_gravity="center_vertical|center_horizontal">

                    <ImageView
                        android:layout_width="115dp"
                        android:layout_height="48dp"
                        android:src="@drawable/sarana"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Sarana Prasarana"
                        android:textColor="@color/white"
                        android:padding="3dp"
                        android:textAlignment="center"
                        android:textStyle="bold"/>
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:id="@+id/imageCard"
                android:layout_width="115dp"
                android:layout_height="90dp"
                android:layout_row="1"
                android:layout_column="0"
                android:layout_margin="8dp"
                app:cardCornerRadius="20dp"
                android:elevation="10dp">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:gravity="center"
                    android:background="#03989E"
                    android:layout_gravity="center_vertical|center_horizontal">

                    <ImageView
                        android:layout_width="115dp"
                        android:layout_height="65dp"
                        android:src="@drawable/guru"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Guru"
                        android:textColor="@color/white"
                        android:padding="3dp"
                        android:textAlignment="center"
                        android:textStyle="bold"/>
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:id="@+id/imageCard"
                android:layout_width="115dp"
                android:layout_height="90dp"
                android:layout_row="1"
                android:layout_column="1"
                android:layout_margin="8dp"
                app:cardCornerRadius="20dp"
                android:elevation="10dp">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:gravity="center"
                    android:background="#03989E"
                    android:layout_gravity="center_vertical|center_horizontal">

                    <ImageView
                        android:layout_width="115dp"
                        android:layout_height="65dp"
                        android:src="@drawable/piala" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Prestasi"
                        android:textColor="@color/white"
                        android:padding="3dp"
                        android:textAlignment="center"
                        android:textStyle="bold"/>
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:id="@+id/imageCard"
                android:layout_width="115dp"
                android:layout_height="90dp"
                android:layout_row="2"
                android:layout_column="0"
                android:layout_margin="8dp"
                app:cardCornerRadius="20dp"
                android:elevation="10dp">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:gravity="center"
                    android:background="#03989E"
                    android:layout_gravity="center_vertical|center_horizontal">

                    <ImageView
                        android:layout_width="115dp"
                        android:layout_height="65dp"
                        android:src="@drawable/jurusan"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Jurusan"
                        android:textColor="@color/white"
                        android:padding="3dp"
                        android:textAlignment="center"
                        android:textStyle="bold"/>
                </LinearLayout>
            </androidx.cardview.widget.CardView>

        </GridLayout>

</RelativeLayout>
   
 <img width="714" alt="3" src="https://github.com/DianaDwiRahayu/TugasPemogramanMobile/assets/101866805/3653abfc-70ac-45af-ad1f-5a05aa279f95">
 
 <p>
 <p> <?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/white"
    android:paddingTop="?attr/actionBarSize">

    <FrameLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/frame_layout"/>

    <com.google.android.material.bottomappbar.BottomAppBar
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/bottomAppBar"
        android:layout_gravity="bottom"
        android:background="@color/white"
        app:fabCradleMargin="10dp"
        app:fabCradleRoundedCornerRadius="50dp">

        <com.google.android.material.bottomnavigation.BottomNavigationView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/bottomNavigationView"
            android:layout_marginEnd="20dp"
            app:labelVisibilityMode="labeled"
            android:background="@android:color/transparent"
            app:menu="@menu/bottom_menu"/>

<img width="714" alt="4" src="https://github.com/DianaDwiRahayu/TugasPemogramanMobile/assets/101866805/86773230-667a-43eb-93bc-dcaee543dc99">

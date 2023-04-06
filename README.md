# Fooddonation
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/teal_200"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="350dp"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"

        app:srcCompat="@drawable/image1"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="80dp" />

    <Button
        android:id="@+id/button"
        android:layout_width="170dp"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"

        android:layout_marginTop="400dp"
        android:backgroundTint="@color/white"

        android:text="REGISTER"
        android:textColor="@color/black"
        android:textSize="25dp"
        tools:layout_editor_absoluteX="145dp"
        tools:layout_editor_absoluteY="497dp" />

</RelativeLayout>

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"

    tools:context=".MainActivity2">



    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="250dp"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"

        app:srcCompat="@drawable/picture"
        tools:layout_editor_absoluteX="80dp"
        tools:layout_editor_absoluteY="-6dp" />
    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="320dp"
        android:layout_marginLeft="70dp"
        android:textSize="25dp"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:text="Username" />
    <EditText
        android:id="@+id/editTextTextPersonName"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="350dp"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:layout_editor_absoluteX="97dp"
        tools:layout_editor_absoluteY="353dp" />
    <TextView
        android:id="@+id/textView4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="420dp"
        android:layout_marginLeft="70dp"
        android:textSize="25dp"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:text="Mobile no." />
    <EditText
        android:id="@+id/editTextPhone"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="460dp"
        android:ems="10"
        android:inputType="phone"

        android:textSize="25dp"
        tools:layout_editor_absoluteX="101dp"
        tools:layout_editor_absoluteY="430dp" />

    <Button
        android:id="@+id/button2"
        android:layout_width="170dp"
        android:layout_height="80dp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="550dp"
        android:backgroundTint="@color/black"
        android:text="REGISTER"
        android:textSize="25dp"

        tools:layout_editor_absoluteX="150dp"
        tools:layout_editor_absoluteY="532dp" />




</RelativeLayout>

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity3"
    android:background="@drawable/gradient_background">

    <FrameLayout
        android:layout_width="370dp"
        android:layout_height="240dp"
        android:layout_marginTop="58dp"
        android:layout_centerHorizontal="true"
        android:background="@color/white">

    </FrameLayout>
    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="On our way"
        android:layout_marginLeft="97dp"
        android:layout_marginTop="145dp"
        android:textSize="45dp"
        android:textStyle="italic"
        android:textColor="#964B00"

        android:gravity="center"

        tools:layout_editor_absoluteX="97dp"
        tools:layout_editor_absoluteY="188dp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center_horizontal"
        android:text="To Ending Hunger"
        android:textStyle="bold"
        android:textSize="43dp"
        android:layout_marginTop="220dp"
        android:layout_marginLeft="35dp"
        tools:layout_editor_absoluteX="46dp"
        tools:layout_editor_absoluteY="262dp" />

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="60dp"
        android:layout_height="48dp"
        android:layout_marginLeft="174dp"
        android:layout_marginTop="70dp"

        app:srcCompat="@drawable/quotes"
        tools:layout_editor_absoluteX="168dp"
        tools:layout_editor_absoluteY="149dp" />

    <Button
        android:id="@+id/button3"
        android:layout_width="140dp"
        android:layout_height="60dp"
        android:layout_marginTop="379dp"
        android:gravity="center_horizontal"
        android:text="SEND"
        android:textSize="25dp"
        android:layout_marginLeft="130dp"

        tools:layout_editor_absoluteX="131dp"
        tools:layout_editor_absoluteY="557dp" />

    <Button
        android:id="@+id/button4"
        android:layout_width="140dp"
        android:layout_height="60dp"
        android:gravity="center_horizontal"
        android:layout_marginTop="480dp"
        android:text="RECEIVE"
        android:textSize="22dp"
        android:layout_marginLeft="130dp"
        tools:layout_editor_absoluteX="149dp"
        tools:layout_editor_absoluteY="491dp" />




</RelativeLayout>

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity4">

    <Button
        android:id="@+id/button5"
        android:layout_width="140dp"
        android:layout_height="60dp"
        android:gravity="center_horizontal"
        android:text="submit"
        android:textSize="25dp"
        android:layout_marginTop="600dp"
        android:layout_centerHorizontal="true"

        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="580dp" />

    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="414dp"
        android:layout_height="855dp"

        android:scaleType="fitXY"
        android:scrollbarAlwaysDrawHorizontalTrack="true"
        android:scrollbarAlwaysDrawVerticalTrack="true"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.666"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.561"
        app:srcCompat="@drawable/sender" />

    <TextView
        android:id="@+id/textView5"
        android:layout_width="103dp"
        android:layout_height="48dp"
        android:text="Name"
        android:layout_marginTop="70dp"
        android:layout_marginLeft="20dp"
        android:textColor="@color/black"
        android:textSize="25dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="61dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/textView5"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginLeft="140dp"
        android:layout_marginTop="60dp"

        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="210dp"
        tools:layout_editor_absoluteY="190dp" />

    <TextView
        android:id="@+id/textView6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Mobile no."
        android:textColor="@color/black"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="138dp"
        android:textSize="25dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="143dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@+id/editTextPhone"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="140dp"
        android:layout_marginTop="122dp"
        android:ems="10"
        android:inputType="phone"

        android:textSize="25dp"
        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="131dp"
        tools:layout_editor_absoluteY="143dp" />

    <TextView
        android:id="@+id/textView7"
        android:layout_width="103dp"
        android:layout_height="48dp"
        android:text="Address"
        android:layout_marginTop="200dp"
        android:layout_marginLeft="20dp"
        android:textColor="@color/black"
        android:textSize="25dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="219dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/textView7"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginTop="184dp"
        android:layout_marginLeft="140dp"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="219dp" />

    <EditText
        android:id="@id/textView7"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginLeft="140dp"
        android:layout_marginTop="240dp"
        android:ems="10"
        android:inputType="textPersonName"


        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="300dp" />

    <TextView
        android:id="@+id/textView8"
        android:layout_width="103dp"
        android:layout_height="65dp"
        android:text="Food Type"
        android:layout_marginTop="300dp"
        android:layout_marginLeft="20dp"
        android:textColor="@color/black"
        android:textSize="25dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="380dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/textView8"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginTop="320dp"
        android:layout_marginLeft="140dp"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="380dp" />
    <TextView
        android:id="@+id/textView9"
        android:layout_width="103dp"
        android:layout_height="65dp"
        android:text="Food Quantity"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="400dp"
        android:textColor="@color/black"
        android:textSize="25dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="475dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/textView9"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginLeft="140dp"
        android:layout_marginTop="420dp"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="475dp" />

</RelativeLayout>

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity5">

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="fitXY"
        android:scrollbarAlwaysDrawHorizontalTrack="true"
        android:scrollbarAlwaysDrawVerticalTrack="true"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.666"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.561"
        app:srcCompat="@drawable/sender" />

    <Button
        android:id="@+id/button5"
        android:layout_width="140dp"
        android:layout_height="65dp"
        android:gravity="center_horizontal"
        android:text="submit"
        android:textSize="25dp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="400dp"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="129dp"
        tools:layout_editor_absoluteY="443dp"
         />

    <TextView
        android:id="@+id/textView5"
        android:layout_width="103dp"
        android:layout_height="48dp"
        android:text="Name"
        android:layout_marginTop="99dp"
        android:layout_marginLeft="50dp"

        android:textColor="@color/black"
        android:textSize="30dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="61dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/editTextTextPersonName"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_marginLeft="150dp"
        android:layout_marginTop="90dp"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="61dp" />
    <TextView
        android:id="@+id/textView6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Mobile no."
        android:layout_marginLeft="50dp"
        android:layout_marginTop="170dp"

        android:textColor="@color/black"
        android:textSize="30dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="143dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@+id/editTextPhone"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:ems="10"
        android:inputType="phone"

        android:textSize="25dp"
        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="131dp"
        tools:layout_editor_absoluteY="143dp" />
    <TextView
        android:id="@+id/textView7"
        android:layout_width="103dp"
        android:layout_height="48dp"
        android:text="Address"
        android:layout_marginTop="245dp"
        android:layout_marginLeft="50dp"
        android:textColor="@color/black"
        android:textSize="30dp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="10dp"
        tools:layout_editor_absoluteY="219dp"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@id/textView7"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_centerHorizontal="true"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="219dp" />

    <EditText
        android:id="@id/textView7"
        android:layout_width="264dp"
        android:layout_height="51dp"
        android:layout_centerHorizontal="true"
        android:ems="10"
        android:inputType="textPersonName"

        android:textSize="25dp"

        tools:ignore="MissingConstraints,SpeakableTextPresentCheck"
        tools:layout_editor_absoluteX="130dp"
        tools:layout_editor_absoluteY="300dp" />


</RelativeLayout>
                           
                           
                         Java Code:
                        
                        package com.firstapp.app;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    private Button button;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        button = (Button) findViewById(R.id.button);
        button.setOnClickListener(new View.OnClickListener(){

            @Override
            public void onClick(View v) {
                Intent intent = new Intent(MainActivity.this, MainActivity2.class);
                startActivity(intent);

            }


        });
    }
}

package com.firstapp.app;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

public class MainActivity2 extends AppCompatActivity {
    private Button button2;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main2);
        button2=findViewById(R.id.button2);
        button2.setOnClickListener(new View.OnClickListener(){
            @Override
            public void onClick(View v){
                Intent intent1=new Intent(MainActivity2.this,MainActivity3.class);
                startActivity(intent1);
            }
        });


    }
}



import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

public class MainActivity3 extends AppCompatActivity {
    private Button button3;
    private Button button4;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main3);
        button3=findViewById(R.id.button3);
        button4=findViewById(R.id.button4);
        button3.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent2=new Intent(MainActivity3.this,MainActivity4.class);
                startActivity(intent2);
            }
        });
        button4.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent3=new Intent(MainActivity3.this,MainActivity5.class);
                startActivity(intent3);
            }
        });
    }
}
package com.firstapp.app;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity4 extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main4);
    }
}


package com.firstapp.app;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity5 extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main5);
    }
}

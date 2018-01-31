# Android Calculator
This is simple android calculator

XML Code
-----------------------------------------------------------------------------------------------------------------------------------
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#000000"
    android:orientation="vertical"
    android:paddingTop="16dp"
    tools:context="com.example.ezel.calculator.MainActivity">

    <TextView
        android:id="@+id/screen"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="end"
        android:paddingRight="16dp"
        android:text="0"
        android:textColor="@android:color/white"
        android:textSize="66sp" />

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <GridLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_centerHorizontal="true"
            android:layout_centerVertical="true"
            android:orientation="vertical"
            android:padding="8dp"
            android:rowCount="6">

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display1"
                android:text="1"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display4"
                android:text="4"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display7"
                android:text="7"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="displayDot"
                android:text="."
                android:textSize="22sp"
                android:theme="@style/Red" />

            <Button
                android:id="@+id/redButtons"
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="clearEntery"
                android:text="CE"
                android:textSize="22sp"
                android:theme="@style/Red" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="clear"
                android:text="C"
                android:textSize="22sp"
                android:theme="@style/Red" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display2"
                android:text="2"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display5"
                android:text="5"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display8"
                android:text="8"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display0"
                android:text="0"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="pi"
                android:text="π"
                android:textAllCaps="false"
                android:textSize="22sp"
                android:theme="@style/Gray" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="euler"
                android:text="e"
                android:textAllCaps="false"
                android:textSize="22sp"
                android:theme="@style/Gray" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display3"
                android:text="3"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display6"
                android:text="6"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="display9"
                android:text="9"
                android:textSize="22sp"
                android:theme="@style/Black" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="equal"
                android:text="="
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="sqrt"
                android:text="√"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="power"
                android:text="ˆ"
                android:textAllCaps="false"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="add"
                android:text="+"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="subtract"
                android:text="-"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="multiply"
                android:text="x"
                android:textAllCaps="false"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="divide"
                android:text="÷"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="minusPositive"
                android:text="±"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_marginRight="4dp"
                android:layout_rowWeight="1"
                android:onClick="absolute"
                android:text="| x |"
                android:textAllCaps="false"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="reminder"
                android:text="%"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="factorial"
                android:text="!"
                android:textSize="22sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="sin"
                android:text="sin"
                android:textAllCaps="false"
                android:textSize="20sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="cos"
                android:text="cos"
                android:textAllCaps="false"
                android:textSize="20sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="tan"
                android:text="tan"
                android:textAllCaps="false"
                android:textSize="20sp"
                android:theme="@style/Orange" />

            <Button
                android:layout_width="0dp"
                android:layout_height="0dp"
                android:layout_columnWeight="1"
                android:layout_gravity="fill"
                android:layout_rowWeight="1"
                android:onClick="approximatelyEqual"
                android:text="≈"
                android:textSize="22sp"
                android:theme="@style/Orange" />

        </GridLayout>
    </RelativeLayout>
</LinearLayout>

Java Code
-----------------------------------------------------------------------------------------------------------------------------------
package com.example.ezel.calculator;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {
    private String firstNumber = "";
    private String secondNumber = "";
    private char operation;
    private double result = 0;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    public void display0(View view) {
        firstNumber += "0";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display1(View view) {
        firstNumber += "1";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display2(View view) {
        firstNumber += "2";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display3(View view) {
        firstNumber += "3";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display4(View view) {
        firstNumber += "4";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display5(View view) {
        firstNumber += "5";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display6(View view) {
        firstNumber += "6";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display7(View view) {
        firstNumber += "7";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display8(View view) {
        firstNumber += "8";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void display9(View view) {
        firstNumber += "9";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void displayDot(View view) {
        firstNumber += ".";
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void add(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '+';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '+';
        } else
            return;
    }

    public void subtract(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '-';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '-';
        } else
            return;
    }

    public void multiply(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '*';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '*';
        } else
            return;
    }

    public void divide(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '/';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '/';
        } else
            return;
    }

    public void reminder(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '%';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '%';
        } else
            return;
    }

    public void power(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '^';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '^';
        } else
            return;
    }

    public void sqrt(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '√';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '√';
        } else
            operation = '√';
    }

    public void factorial(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = '!';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = '!';
        } else
            return;
    }

    public void sin(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = 's';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = 's';
        } else
            operation = 's';
    }

    public void cos(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = 'c';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = 'c';
        } else
            operation = 'c';
    }

    public void tan(View view) {
        if (result != 0) {
            secondNumber = Double.toString(result);
            firstNumber = "";
            operation = 't';
        } else if (!firstNumber.equals("")) {
            secondNumber = firstNumber;
            firstNumber = "";
            operation = 't';
        } else
            operation = 't';
    }

    public void minusPositive(View view) {
        double number = Double.parseDouble(firstNumber) * -1;
        firstNumber = Double.toString(number);
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void absolute(View view) {
        double number = Double.parseDouble(firstNumber);
        firstNumber = Double.toString(Math.abs(number));
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void pi(View view) {
        firstNumber = String.format("%.5f", Math.PI);
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void euler(View view) {
        firstNumber = String.format("%.5f", Math.E);
        result = 0;
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText(firstNumber);
    }

    public void equal(View view) {
        TextView screen = (TextView) findViewById(R.id.screen);
        String str = "";
        int number = 1;
        int numberOfZeros = 0;
        int numbersAfterDot = 0;
        String res = "";
        if (firstNumber.equals("") && secondNumber.equals(""))
            return;
        else if (result != 0) {
            if (res.equals("Error"))
                screen.setText(res);
            else if (Double.toString(result).charAt(Double.toString(result).length() - 1) == '0' && Double.toString(result).charAt(Double.toString(result).length() - 2) == '.')
                screen.setText(String.format("%.0f", result));
            else {
                res = (String.format("%.6f", result));
                while (res.charAt(res.length() - number) == '0') {
                    numberOfZeros++;
                    number++;
                }
                numbersAfterDot = res.substring(res.indexOf(".")).length() - numberOfZeros - 1;
                str = "%." + numbersAfterDot + "f";
                screen.setText(String.format(str, result));
            }
        } else {
            switch (operation) {
                case '+':
                    result = Double.parseDouble(secondNumber) + Double.parseDouble(firstNumber);
                    break;
                case '-':
                    result = Double.parseDouble(secondNumber) - Double.parseDouble(firstNumber);
                    break;
                case '*':
                    result = Double.parseDouble(secondNumber) * Double.parseDouble(firstNumber);
                    break;
                case '/':
                    try {
                        if (!firstNumber.equals("0"))
                            result = Double.parseDouble(secondNumber) / Double.parseDouble(firstNumber);
                        else
                            throw new Exception();
                    } catch (Exception e) {
                        res = "Error";
                    }
                    break;
                case '%':
                    try {
                        if (!firstNumber.equals("0"))
                            result = Double.parseDouble(secondNumber) % Double.parseDouble(firstNumber);
                        else
                            throw new Exception();
                    } catch (Exception e) {
                        res = "Error";
                    }
                    break;
                case '^':
                    result = Math.pow(Double.parseDouble(secondNumber), Double.parseDouble(firstNumber));
                    break;
                case '√':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.sqrt(Double.parseDouble(secondNumber));
                    break;
                case '!':
                    result = 1;
                    for (int i = 1; i <= Double.parseDouble(secondNumber); i++)
                        result *= i;
                    break;
                case 's':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.sin(Double.parseDouble(secondNumber));
                    break;
                case 'c':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.cos(Double.parseDouble(secondNumber));
                    break;
                case 't':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.tan(Double.parseDouble(secondNumber));
                    break;
            }
        }
        if (result != 0 || res.equals("Error")) {
            if (res.equals("Error"))
                screen.setText(res);
            else if (Double.toString(result).charAt(Double.toString(result).length() - 1) == '0' && Double.toString(result).charAt(Double.toString(result).length() - 2) == '.')
                screen.setText(String.format("%.0f", result));
            else {
                res = (String.format("%.6f", result));
                while (res.charAt(res.length() - number) == '0') {
                    numberOfZeros++;
                    number++;
                }
                numbersAfterDot = res.substring(res.indexOf(".")).length() - numberOfZeros - 1;
                str = "%." + numbersAfterDot + "f";
                screen.setText(String.format(str, result));
            }
        }
        firstNumber = "";
    }

    public void approximatelyEqual(View view) {
        TextView screen = (TextView) findViewById(R.id.screen);
        String str = "";
        int number = 1;
        int numberOfZeros = 0;
        int numbersAfterDot = 0;
        String res = "";
        if (firstNumber.equals("") && secondNumber.equals(""))
            return;
        else if (result != 0) {
            if (res.equals("Error"))
                screen.setText(res);
            else if (Double.toString(result).charAt(Double.toString(result).length() - 1) == '0' && Double.toString(result).charAt(Double.toString(result).length() - 2) == '.')
                screen.setText(String.format("%.0f", result));
            else {
                res = (String.format("%.1f", result));
                while (res.charAt(res.length() - number) == '0') {
                    numberOfZeros++;
                    number++;
                }
                numbersAfterDot = res.substring(res.indexOf(".")).length() - numberOfZeros - 1;
                str = "%." + numbersAfterDot + "f";
                screen.setText(String.format(str, result));
            }
        } else {
            switch (operation) {
                case '+':
                    result = Double.parseDouble(secondNumber) + Double.parseDouble(firstNumber);
                    break;
                case '-':
                    result = Double.parseDouble(secondNumber) - Double.parseDouble(firstNumber);
                    break;
                case '*':
                    result = Double.parseDouble(secondNumber) * Double.parseDouble(firstNumber);
                    break;
                case '/':
                    try {
                        if (!firstNumber.equals("0"))
                            result = Double.parseDouble(secondNumber) / Double.parseDouble(firstNumber);
                        else
                            throw new Exception();
                    } catch (Exception e) {
                        res = "Error";
                    }
                    break;
                case '%':
                    try {
                        if (!firstNumber.equals("0"))
                            result = Double.parseDouble(secondNumber) % Double.parseDouble(firstNumber);
                        else
                            throw new Exception();
                    } catch (Exception e) {
                        res = "Error";
                    }
                    break;
                case '^':
                    result = Math.pow(Double.parseDouble(secondNumber), Double.parseDouble(firstNumber));
                    break;
                case '√':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.sqrt(Double.parseDouble(secondNumber));
                    break;
                case '!':
                    result = 1;
                    for (int i = 1; i <= Double.parseDouble(secondNumber); i++)
                        result *= i;
                    break;
                case 's':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.sin(Double.parseDouble(secondNumber));
                    break;
                case 'c':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.cos(Double.parseDouble(secondNumber));
                    break;
                case 't':
                    if (firstNumber != "")
                        secondNumber = firstNumber;
                    result = Math.tan(Double.parseDouble(secondNumber));
                    break;
            }
        }
        if (result != 0 || res.equals("Error")) {
            if (res.equals("Error"))
                screen.setText(res);
            else if (Double.toString(result).charAt(Double.toString(result).length() - 1) == '0' && Double.toString(result).charAt(Double.toString(result).length() - 2) == '.')
                screen.setText(String.format("%.0f", result));
            else {
                res = (String.format("%.1f", result));
                while (res.charAt(res.length() - number) == '0') {
                    numberOfZeros++;
                    number++;
                }
                numbersAfterDot = res.substring(res.indexOf(".")).length() - numberOfZeros - 1;
                str = "%." + numbersAfterDot + "f";
                screen.setText(String.format(str, result));
            }
        }
        firstNumber = "";
    }

    public void clearEntery(View view) {
        if (firstNumber.length() == 0)
            return;
        if (firstNumber.length() - 1 == 0) {
            clear(view);
        } else {
            firstNumber = firstNumber.substring(0, firstNumber.length() - 1);
            TextView screen = (TextView) findViewById(R.id.screen);
            screen.setText(firstNumber);
        }
    }

    public void clear(View view) {
        firstNumber = "";
        secondNumber = "";
        TextView screen = (TextView) findViewById(R.id.screen);
        screen.setText("0" + firstNumber);
    }
}

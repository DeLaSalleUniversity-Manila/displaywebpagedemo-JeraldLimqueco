# displaywebpagedemo
displaywebpagedemo-JeraldLimqueco created by Classroom for GitHub

This assignment illustrates how to display a webpage from an Android application.

## Problem:

Implement an Android application that displays DLSU webpage on launch.

## Basic WebView usage in MainActivity.java:

```Java
   public void displayWebpage(){
        WebView webview = (WebView) findViewById(R.id.viewwebpagedlsu);
        webview.loadUrl("http://www.dlsu.edu.ph");
    }
```


# Rapport

Har ändrat namn på appen till isakApp.
Sedan aktiverat internetåtkomst.
Skapat en WebView-element.
Skapat en WebViewClient som lagt till WebViewn.
Aktiverat JavaScript till WebViewClienten.
Skapat en subfolder och html-sida som asset.
Implementerat showExternal... och showInternalWebPage()
Att ladda den url jag gett dem.
External laddar his.se, Internal laddar about.html.

Koden under aktiverar javascript till myWebView

```
WebView myWebView = (WebView) findViewById(R.id.my_webview);
        WebSettings webSettings = myWebView.getSettings();
        webSettings.setJavaScriptEnabled(true);
}
```



Bilder läggs i samma mapp som markdown-filen.

![](internalPage2.png)
![](externalPage.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.

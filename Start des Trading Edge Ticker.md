

  Wenn du die HTML-Datei direkt öffnest (file://), blockt der Browser manchmal externe APIs. Dann einmalig im Terminal:

  python -m http.server 8080

  → dann im Browser http://localhost:8080/Ticker-Scanner.html öffnen. Danach funktioniert es dauerhaft.

  Focus List und T+3 machst du ja direkt in TradingView — das ist der richtige Weg, da hast du Live-Charts, Alerts und die
  RS-Linie direkt dabei.
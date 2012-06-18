CountryCode
===========

ISO 3166-1 (alpha-2/alpha-3/numeric) country code enum in Java.

License
-------

Apache License, Version 2.0

Download
--------

    git clone git://github.com/TakahikoKawasaki/CountryCode.git

Javadoc
-------

[CountryCode Javadoc](http://takahikokawasaki.github.com/CountryCode/index.html)

Example
-------

    CountryCode cc = CountryCode.getByCode("JP");

    System.out.println("Country name = " + cc.getName());                  // "Japan"
    System.out.println("ISO 3166-1 alpha-2 code = " + cc.getAlpha2());     // "JP"
    System.out.println("ISO 3166-1 alpha-3 code = " + cc.getAlpha3());     // "JPN"
    System.out.println("ISO 3166-1 numeric code = " + cc.getNumeric());    // 392

Author
------

Takahiko Kawasaki, Neo Visionaries Inc.
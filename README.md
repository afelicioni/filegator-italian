# filegator-italian
This repo is intended to provide italian language support for [FileGator][1]

## the need about this
Since used [cloud-asterisk][2] to test a project, noted that TelREX interface was missing italian language translation. So I'm going to release it on [GitHub][3]
Even on [FAQ page][4] (visited on 2015-01-09) from the original vendor is unclear about full up to date language support
> Can I translate FileGator?
>
> This script contains a single language file and can be easily translated. You can download language files from here: http://file-gator.com/gator/languages.zip
> Currently available languages: English, French, German, Dutch, Russian, Polish, Portuguese, Spanish, Swedish, Persia, Serbian, Romanian, Korean, Finnish
I ended up in rewriting it, using as template the found one from [supported languages file][5].

## how to
Copy `languages/italian.php` from this repo to your existing TelREX setup, can be like `/telrex/filegator/languages`
Edit `/telrex/filegator/configuration.php` on line 22, like the following
```php
'language' => 'italian',
```

## license
See [LICENSE][6]

[1]: http://www.file-gator.com/
[2]: https://github.com/sergibondarenko/cloud-asterisk
[3]: https://github.com/afelicioni/filegator-italian
[4]: http://www.file-gator.com/gator/faq.php
[5]: http://www.file-gator.com/gator/languages.zip
[6]: LICENSE

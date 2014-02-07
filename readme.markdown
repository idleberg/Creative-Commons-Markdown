# Creative Commons 4.0 Markdown

On November 25th, 2013, [Creative Commons](http://creativecommons.org/) announced their next generation licenses: [Creative Commons 4.0](https://creativecommons.org/weblog/entry/40768). By default, these are available as [HTML](http://creativecommons.org/licenses/) or [plaintext](http://creativecommons.org/weblog/entry/41127). This project adds [Markdown](http://daringfireball.net/projects/markdown/)-formatted licenses to that list.

Unfortunately, the output currently varies on different Markdown viewers, in particular when it comes to indentation levels:

* [v0.1](https://github.com/idleberg/Creative-Commons-4.0-Markdown/tree/0.1/licenses) uses tabs to indent text,  might cause some blocks to be interpreted as code (e.g. on GitHub)

* [v0.2](https://github.com/idleberg/Creative-Commons-4.0-Markdown/tree/0.2/licenses) uses spaces to indent text, results in less readable files when viewed as plain text

If you any suggestion on the formatting, feel invited to contribute.

## Licenses

* `BY` [Attribution](licenses/by.markdown)
* `BY-NC` [Attribution-NonCommercial](licenses/by-nc.markdown)
* `BY-NC-ND` [Attribution-NonCommercial-NoDerivatives](licenses/by-nc-nd.markdown)
* `BY-NC-SA` [Attribution-NonCommercial-ShareAlike](licenses/by-nc-sa.markdown)
* `BY-ND` [Attribution-NoDerivatives](licenses/by-nd.markdown)
* `BY-SA` [Attribution-ShareAlike](licenses/by-sa.markdown)
* `C0` [CC0](licenses/zero.markdown)

## File extension

There's a plethora of Markdown file extensions, but I have decided to go with `markdown`. Read why:

*"We no longer live in a 8.3 world, so we should be using the most descriptive file extensions. It’s sad that all our operating systems rely on this stupid convention instead of the better creator code or a metadata model, but great that they now support longer file extensions."*  
Hilton Lipschitz ([via](http://hiltmon.com/blog/2012/03/07/the-markdown-file-extension/))

*"…the only file extension I would endorse is “.markdown”, for the same reason offered by Hilton Lipschitz"*  
John Gruber, creator of Markdown ([via](http://daringfireball.net/linked/2014/01/08/markdown-extension))

## Contribute

If you notice any mistakes in content or formatting, please send a pull request with your correction.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/idleberg/creative-commons-4.0-markdown/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

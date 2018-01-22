---
views:
    main:
        template: default/content
        data:
            class: blog

    byline: false
    share-this: false
    article-toc: false

    blog-list:
        region: main
        template: default/blog-list
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                items: 10

...
Projektblogg
--------------

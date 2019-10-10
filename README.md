# ace-shexc-user
Simple example using ace-shexc-mode.

Try it online at https://shexspec.github.io/ace-shexc-user/
or with some pre-filled examples:
* [annotation example](https://shexspec.github.io/ace-shexc-user/?schema=%3CS%3E%20%7B%0D%0A%20%20%3Cp1%3E%20%40%3Cfoo%3E%20%2F%2F%20rdfs%3Alabel%20%22p1%22%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20rdfs%3Adescription%20%22desk%20for%20p1%22%20%3B%0D%0A%20%20%3Cp2%3E%20.%0D%0A%7D) (?schema=…}
* [EXTRA example](https://shexspec.github.io/ace-shexc-user/?schemaURL=https://raw.githubusercontent.com/shexSpec/shexTest/master/schemas/3EachdotExtra3NLex.shex) (?schemaURL=…)
* [kitcheSink example](https://shexspec.github.io/ace-shexc-user/?schemaURL=https://raw.githubusercontent.com/shexSpec/shexTest/master/schemas/kitchenSink.shex) (?schemaURL=…)
or with a [form like this](form.html) (see [example on shex.io](http://shex.io/webapps/ace-shexc-form)) in your own page (sorry, github markdown won't render the form):
``` html
    <form method="get" action="https://shexspec.github.io/ace-shexc-user/">
      <p>
        <input type="text" name="schemaURL"/><br/>
        <input type="submit" value="Submit"/>
      </p>
    </form>
```

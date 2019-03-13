<img src="http://www.zold.io/logo.svg" width="92px" height="92px"/>

[![Donate via Zerocracy](https://www.0crat.com/contrib-badge/CB28FH2NR.svg)](https://www.0crat.com/contrib/CB28FH2NR)

This is a collection of HAML templates for
this [web page](https://wts.zold.io). You can create your
own template, submit a pull request, and we will merge it into
this repository. When it's merged, you can use it in the page
like this:

```
https://wts.zold.io/quick?haml=simple
```

The HAML template will be downloaded on the fly.

If you want to test it locally, you have to checkout
[this repo](https://github.com/zold-io/wts.zold.io) first. Then, open
their file `views/quick_default.haml` in any text editor you want. Make
sure you have [all prerequisites](https://github.com/zold-io/wts.zold.io#how-to-contribute)
installed. Then, in the directory of that repo, run this:

```bash
$ bundle update
$ bundle exec rake run
```

Then, open this URL in your browser: `http://localhost:4567/quick`.
Now you can make changes to the `quick_default.haml` file and they will
re-render in the browser, immediately. When done, use that file as a new
template and send it here in a pull request.

If any issues, [submit a ticket](https://github.com/zold-io/quick/issues).

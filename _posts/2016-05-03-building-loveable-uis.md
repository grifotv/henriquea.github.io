---
layout: post
title:  "Building Loveable UIs"
date:   2016-05-03 21:25:52 +0000
category: writing
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight css %}
@import "base.scss";
@import "base.scss";
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

Finally some JavaScript fun:

{% highlight javascript %}
const styles = {
  root: {
    padding: '1em',
    ':container (max-width: 300px)': {
      padding: '0.5em'
    }
  },
  label: {
    fontSize: '1.2em',
    ':container (max-width: 300px)': {
      fontSize: '1em'
    }
  }
};

const Button = () => (
  <div style={ styles.root }>
    <div style={ styles.label }>Button</div>
  </div>
);

export default eq(Button);
{% endhighlight %}

How about a list?

- What if
- What else
- Whatever

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

<article class="markdown-body entry-content p-5" itemprop="text"><h1><a id="user-content-blogger-related-posts-widget" class="anchor" aria-hidden="true" href="#blogger-related-posts-widget"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Blogger Related Posts Widget</h1>
<p>Blogger Related Posts Widget is a script that displays a list of related posts below the current post. It does so by finding posts with matching labels. Here is an <a href="https://salman-w.blogspot.com/2012/09/blogger-related-posts.html" rel="nofollow">overview of the script</a>.</p>
<h2><a id="user-content-features" class="anchor" aria-hidden="true" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Features</h2>
<ul>
<li>Light weight vanilla JavaScript code — no JavaScript framework required</li>
<li>Customizable widget layout — just about everything can be styled using CSS</li>
<li>Post thumbnails support — because a thumbnail image is worth a thousand words</li>
<li>Google Analytics integration — clicks are logged in Google Analytics</li>
<li>Lazy-loadable — the script can be loaded asynchronously</li>
<li>Easy installation — does not require editing Blogger template</li>
<li>Faster than most other related post scripts — uses one request to fetch related posts</li>
</ul>
<h2><a id="user-content-prerequisites" class="anchor" aria-hidden="true" href="#prerequisites"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prerequisites</h2>
<p>In order for the script to work make sure that:</p>
<ul>
<li>Blog post feeds are enabled</li>
<li>Blog posts are labeled properly</li>
</ul>
<h2><a id="user-content-installation" class="anchor" aria-hidden="true" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Installation</h2>
<p>The easiest way to install the script on your blog is to use the "Add a Gadget" option in Blogger dashboard to insert a "HTML/JavaScript" gadget. The gadget can go anywhere but below the footer would be best. Use the following HTML5 content:</p>
<pre><code>&lt;script src="//cdn.rawgit.com/salmanarshad2000/blogger-related-posts-widget/v1.0.4/related-posts.min.js" defer&gt;&lt;/script&gt;
</code></pre>
<h2><a id="user-content-css-styles" class="anchor" aria-hidden="true" href="#css-styles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CSS Styles</h2>
<p>You must add some CSS rules to your Blogger style-sheet in order to customize the appearance of the related posts. You can use the following CSS rules to get started:</p>
<pre><code>#blogger-related-posts ul {
    padding: 0;
    list-style-type: none;
    text-align: center;
}
#blogger-related-posts li {
    float: left;
    margin: 0 1%;
    width: 18%;
}
#blogger-related-posts a {
    display: block;
}
#blogger-related-posts span {
    display: block;
    margin: 0 auto .5em;
    width: 72px;
    height: 72px;
}
#blogger-related-posts ul:after {
    content: "";
    display: block;
    clear: both;
}
</code></pre>
</article>

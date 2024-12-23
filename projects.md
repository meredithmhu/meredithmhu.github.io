---
layout: default
title: My Projects
---

<h1 class="header-container">My Projects</h1>

<div class="content-container">
    Here are my CS projects. Click on "View Code Snippet" to expand and see a sample of code from the project. Each item in "View Technologies" is clickable and links to an online webpage with more information.
</div>

<div class="project-box">
    <h2>
        <a class="project-title" href="https://github.com/meredithmhu/meredithmhu.github.io" target="_blank">My Website</a>
    </h2>
    <span>This is the GitHub repository for this website. I created this website to showcase my projects and interests in CS.</span>
    <p>Lines of Code: 500+ | Hours Spent: 10</p>
    
    <p>
    <span class="technologies">
        Technologies Used:
        <a href="https://jekyllrb.com" target="_blank">Jekyll</a>, 
        <a href="https://www.ruby-lang.org" target="_blank">Ruby</a>, 
        <a href="https://pages.github.com" target="_blank">GitHub Pages</a>, 
        <a href="https://www.markdownguide.org" target="_blank">Markdown</a>
    </span>
    </p>

    <details>
        <summary>View Code Snippet</summary>
        <pre>
{% highlight html %}
<div class="project-box">
    <h2>
        <a class="project-title" href="https://github.com/meredithmhu/meredithmhu.github.io" target="_blank">My Website</a>
    </h2>
    <p>This is the GitHub repository for this website. I created this website to showcase my projects and interests in CS.</p>
    <p>Lines of Code: 500+ | Hours Spent: 20+</p>
{% endhighlight %}
        </pre>
    </details>
    
</div>

<div class="project-box">
    <h2>
        <a class="project-title" href="https://github.com/cucapra/caiman" target="_blank">Caiman Benchmarks</a>
    </h2>
    <p>I was a research assistant in a programming languages and architecture lab while at school, and worked on an optimizing compiler for heterogeneous language processing called Caiman.</p>
    <p>Lines of Code: 1000+ | Hours Spent: 100+</p>

    <p>
    <span class="technologies">
        Technologies Used:
        <a href="https://en.wikipedia.org/wiki/Assembly_language" target="_blank">Assembly</a>, 
        <a href="https://www.rust-lang.org" target="_blank">Rust</a>, 
        <a href="https://git-scm.com" target="_blank">Git</a>
    </span>
    </p>
    
    <details>
        <summary>View Code Snippet</summary>
        <pre>
{% highlight rust %}
type i64;
event %event0;
buffer_space %buffspace;
native_value %ni64 : i64;

function @sub(i64, i64) -> i64;
function @mult(i64, i64) -> i64;
function @main() -> i64;

external-cpu-pure[impl @sub] %sub(i64, i64) -> i64;
external-cpu-pure[impl @mult] %mult(i64, i64) -> i64;

value[impl default @main] %foo() -> i64 {
  //constants 
    %x = constant %ni64 10;
    %y = constant %ni64 5;
    %z = constant %ni64 -3;

    %x_t = call @mult(%y, %z);

    %something = extract %x_t 0;

    %y_t = call @sub(%x, %something);

    %r = extract %y_t 0;
    return %y;
}
{% endhighlight %}
        </pre>
    </details>
    
</div>

<div class="content-container">
    If you'd like to see more of my work, check out my&nbsp;<a href="https://github.com/meredithmhu" target="_blank">GitHub profile</a>.

</div>

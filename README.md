# ReddAnalyz
Analyzing Reddit posts, authors, contents ... etc.

- Find your fellow struggling programmers, or a guru, or an investor, by mining Reddit posts ...

So I made the following posts on Reddit in the last 24 hours.

- https://www.reddit.com/r/CryptoCurrency/comments/fnzpxh/nroulette_a_novel_open_source_online_roulette/

N-Roulette: a novel open source online roulette project, to reward programmers and roulette ladies with ID-less interface to cryptocurrencies

- https://www.reddit.com/r/programming/comments/fnmabd/nroulette_the_fairest_roulette_built_using_idless/

N-Roulette: the fairest roulette built using ID-less transaction protocol

N-Roulette is based on, amongst others, a project on Forth like Stack Machine Shell that I started in the second half of 2017: 

https://github.com/udexon/GOEHDOM/blob/master/Phos_Smashlet.md

In short, it is a magical invention (I thought) which enables you (programmers) to write code in Reverse Polish Notation as a shell script to interface to ANY KNOWN programming language, where the example above demonstrates the cases for PHP and JavaScript.

The grand (or beautiful, I hope) idea is to get anyone, from veteran programmers to non-programmers, to learn RPN (which is no more complicated than Excel script, really), and work together to create "Free Software Revolution 2.0", just like how RMS (you should know who he is) cloned the Unix tools and created Free Software Revolution 1.0. Only this time, our aim is to clone the whole social networks infrastructure, represented by MAGA+F (Microsoft Apple Google Amazon Facebook).

You see, FSR1 was successful not because it was innovative, but it simply cloned the super powerful Unix tools. So in FSR2, we do not aim to surpass MAGA+F, but simply to beat them on COSTS, and in doing so, train the next generations of programmers, using RPN, or a version of RPN which I call Phos ("light" in Greek, as in "genetheto phos" -- "let there be light" -- "fiat lux"). But to do so, we need a tool that is better and easier to use than the tools in FSR1. Over the years, I believe I have perfected the tools -- not that they need a lot of polishing to start with, as you can see by browsing my repositories. So now is the time to publicize it.

But here is where I learn even more hard lessons -- how to make your project stand out in a sea of noise in /r/programming?

Hence ReddAnalyz -- you don't -- you simply discover programmers with similar interests as yours, and rank them. Or at least that is the hypothesis we are testing now.

So I like to blog about my ideas on GitHub and get collaborators. I understand some of you may criticize this approach. But why not?

So the first step I am planning are the following:

1. Use simple_html_dom.php (a very old HTML parser) to parse the contents of /r/programming.
2. Produce the histogram of the words in the subject line of the posts.
3. Do the above using Phos in PHP.
4. Port the above to JavaScript.

I shall continue to post as I find time to code and write more on this blog.

In the meantime, feel free to leave a message here or on /r/programming.

And of course, it goes without saying, in the spirit of free software, you are welcome to participate and FORK IT!!


```
Phos_PHP$ php phos.php Documents/N-Roulette/programming.html fgh: h3 find: cx: dup: ON ECHO bv:   A l: 1 - 2 pick: over: dup: esp:     i:  st:  // esp: nl:    esp:   nl: nl:  A bnz:  nl: > o_programming.txt
```

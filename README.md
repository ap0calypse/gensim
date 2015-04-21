# gensim
a very stupid, but also funny genetic recombination 'simulator'

Latest screenshot:
------------------

![screenshot gensim](screenshot.png "Screenshot")


Prerequisites:
--------------

Perl Modules:
    
        - Term::ReadLine           (archlinux-package: perl-term-readline)


What the hell is this?!
-----------------------

Well, this little project evolved out of a little exercise. Basically, it's
veeeeery simple. Each creature you spawn, has a random genome with a length
of 100 characters. These characters are A, C, G and T.

Each genome has it's sections, and every section has it's own purpose. To
clarify what I mean, look at the genome sequence of one of my creatures:

GGATAGTTCTCCCCTTCACTCAAAGGACCACTAGGTATCTGGCAACCTCGTACAACCCGTTCGGAAGCTGGGTGCCGGAGCTCACGGTTGGTATTCAAAG
[   Background     ][   Color          ][   Form           ][   Symbols        ][   Junk DNA :P    ]

As you can see, there are sections for every aspect of the creature so far.
New ideas are highly appreciated.

Recombination is pretty random, take a look at the source to get a clue.

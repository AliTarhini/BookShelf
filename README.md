# BookShelf

## In which we clone GoodReads.com



## Readers

The great American novelist and essayist, Elwyn Brooks ('E. B.') White wrote, in
the November 30, 1935 issue of _The New Yorker_, a short essay, "Irtnog," about the struggle
between readers and writers

> Along about 1920 it became apparent that more things were being written than
> people had time to read.  That is to say, even if a man spent his entire time
> reading stories, articles, and news, as they appeared in books, magazines, and
> pamphlets, he fell behind.  This was no fault of the reading public; on the
> contrary, readers made a real effort to keep pace with writers, and utilized
> every spare moment during their walking hours.

Obviously, in these days of even further accelerated production, in print and
especially online, readers need a way to hone in on those books they actually
want to read.

Enter websites like [GoodReads](https://www.goodreads.com/), which allow readers
to connect with other readers with similar tastes, and exchange information.


## Server-side

The backend is a [Rails](http://rubyonrails.org/).


### Authentication

Authentication is handled using the 'devise' gem.


### Database model

The central persisted entities are:

* Users
* Books
* CategorieS
* Reviews


## To Do

The implementation as it stands covers the basic functionality, but other features
would be nice. Particularly those involved in interacting users. Thus we would like

    - messaging between users
    - user recommendations (one user to another)
    - notifications of recent activity of other users
    - commenting on things other than books. Comments on authors, genres, reviews, etc.

futurepress
===========

An HTML5 Framework for EBooks

We are going to make an HTML5 framework geared specifically towards Books.
⁃  Think of it as ‘Twitter Bootstrap for books.’
⁃	It will be based on HTML5 boilerplate, which already provides a nice framework for responsive templates that are supported across browsers and devices.
⁃	Perhaps we will also use a few JavaScript libraries and elements from Twitter Bootstrap.
⁃	The goal is to start an HTML5 framework that is geared specifically towards longer texts, like books.
Why is this needed?
⁃	Formats like Epub3 support HTML5 but publishers are left to do the dirty work themselves. The only framework that really exists (we don’t talk about Inkling) for enhanced eBooks is iBooks Author. Publishers are left in the dark with these things.
⁃	Tools that help people make things usually go over nicely. 
⁃	Something like this would be helpful even if something like Epub3 takes off as the new format: since future formats are likely to be based on HTML5. 
What will we code/design over winter?
⁃	Aspects of things we’ve wanted all along: annotations, comments, Evernote integration, and more. But first… we’ll focus on replicating all functionality that eBooks currently have.
  ⁃	Search: You can search the entire text of a book. This is extremely useful. However, when we break the TDO book into sections, we won’t be able to search the whole book, only that page.
  ⁃	Pagination/layouts: this is a big one that I think will require a little bit of thought and ingenuity, but it’s arguably the most important. I don’t think people mind a bit of scrolling, but we need to put options for this in the hands of the publisher. Some people want just a single page in a book, and they tap their finger to go onto the next page. Of course this depends on the book. Sometimes a bit of scrolling isn’t bad (that is the web default), but the challenge for our framework is creating OPTIONS. Perhaps we can steal some ideas from Readium. 
  ⁃	Making/optimizing views for desktop, tablets, and mobile (again, we can base these off boilerplate or Twitter Bootstrap)
  ⁃	Navigation: I like how this book does it’s navigation (http://book.pressbooks.com/chapter/book-and-the-internet-hugh-mcguire)
  ⁃	Click on the chapter, and then click on the table of contents, a slick navigation menu unfolds.
    ⁃	Also that article informed some of my thinking on this whole thing.
    ⁃	We need a way of easily/quickly going through different sections.
    ⁃	Perhaps we can even replicate for the web the slider at the bottom of iBooks that allows you to skip through page numbers. 
  ⁃	Making page turns fast: one of things that sucks about reading long texts on the web is that going to the next page takes a long time, especially if you are somewhere with slow internet. Perhaps a simple script that preloads the next couple of pages. Fred, perhaps you have some thoughts about this from looking at Readium.
  ⁃	Dictionary:  should be able to use an API from some place to provide this functionality.  
  ⁃	Font Changer: While I’m a big fan of having a default layout, I do realize that some people (not any of us young people) need to have larger font sizes to read. A simple button that enlarges or decreases font size would be easy to implement. 
  ⁃	Can you think of anything else?
⁃	The branding/GitHub repository for this open source project. This is important for attracting developers to the project. Making a good website that clearly explains the project is essential. 
⁃	HTML5 local storage… this could be the trickiest and something that might come later.

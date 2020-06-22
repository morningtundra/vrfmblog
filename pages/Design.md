---
layout: default 
---

# Design
 - [Design Brief](#design-brief)
 - [Cover Design & Dust Jackets](#cover-design--dust-jackets)
 - [Interior Book Design](#interior-book-design)
 - [Typography & Typesetting](#typography--typesetting)
 - [Website Landing Pages](#website--landing-pages)

During your book [Planning](Planning.md) you will have been collecting data like  snippets, photos, measurements, notes, fonts, doodles, color palets etc. If you haven't done so, dump them all in a document called, Design Brief.

# Design Brief
A formally written design brief serves two purposes.

1. Capture and clarify your goals and criteria
2. Saves repeating yourself when engaging subcontractors

The internet is full of guidance on how to write a graphic design brief. For a book, keep it to two pages or less. At a minimum it should include the following,

* A demographic description of your target reader
* Trim size
* Target word and page count
* Planned price point or range
* Photo examples of what you like and a description of why
* Links to competing books
* Suggested color pallet and font styles

# Color
For non-fiction, use of color is almost essential and forms a crucial part of your book branding. A color palette or theme should be identified early in the conceptual design process and needs to meet some criteria,
* Consistent and complementary with any photography or raster assets
* Compliant with CMYK print standards and 'color profiles' where necessary
* Distinctive when compared to the nearest competing titles
* Complementary to the tone and style of the book content (e.g. classic and conservative vs punky and hip)
* Chosen with some awareness of basic color theory

Ensure the chosen palette can be carried over to marketing and advertising assets, including social media profiles. 

# Cover Design & Dust Jackets
Contrary to popular opinion, yes you *can* design your own cover. If you want to, or can't afford a graphic designer, go ahead and do your own. This advice does not apply equally to fiction.

While [assessing the compatitive landscape](Planning.md) during your Planning you will have seen many cover designs. While your personal preferences are important you must dispassionately decide,

* Which designs stand out on bookstore shelves?
* Which work equally well at thumbnail size on Amazon?
* What does the #1 Best Seller look like?
* What do these titles have in common?

# Interior Book Design
You can do your interior layout and typesetting yourself if you are proficient with a Desktop Publishing tool (DTP) like InDesign (or  Quark Express or open source [Scribus](https://www.scribus.net/).) However, this can be a very time consuming undertaking, even if you start with one of the many InDesign templates you can find on the internet. 

If you plan to perform the interior layout, it is important to read the [File Format or File Generation](https://www.ingramspark.com/hubfs/downloads/file-creation-guide.pdf) guidelines of the POD Publisher. Read this first to determine appropriate margins, gutter and bleed sizes and then setup your DTP template pages. Changing this later can be very tedious and frustrating.

Make sure you become familiar with basic book design conventions like 'orphans', 'widows', page numbering and layout conventions like use of roman numerals for front matter and 
starting new chapters on the right side of a spread. While all of this is learnable, it is time consuming and justifies the use of a professional designer.

If your book is complex, and you want a highly professional result, contact Jenny Goodhand at The Refinery Designs

# Website & Landing Pages

There is an important distinction between a website and a product landing page. For the purposes of selling a few books, a collection of one-page landing pages is more than sufficient. This is preferable to a full-blown website with complex cross-linking.

The purpose of a landing page is to convert a visitor into a book sale. Outbound or cross-site links distract a potential customer from responding to the Call To Action (Buy Now).

The optimum structure of a book landing page is well established. It includes the following elements,

* Product Image(s) or Video (book trailer)
* Social Proof (testimonials)
* Call to action (buy button)
* Short concise sales copy (description)
* Short author blurb
* Guarantees & Assurances
* Seller contact info

The sequence of these elements may vary and A/B testing may be useful to optimize the effectiveness. This is a pretty standard landing page setup

# Website Performance

* [webpagetest.org](https://webpahetest.org)

# Website Images

Resize your images with this Terminal (command line) tool from Imagemagick

>  convert BM422.jpg -sampling-factor 4:2:0 -strip -quality 85 -interlace JPEG -colorspace sRGB Opt_BM422.jpg 
<h1 align="center">fm-favs-scraper 🗄️</h1>

> Grabs meta information of bookmarked courses on Frontend Masters and sends to Airtable page
 

## Preface  💬️

[Frontend Masters](https://frontendmasters.com/courses) is a great site with courses for `frontend engineers` where 
you can find both deep UI engineering stuff and some unusual courses on Security, Rust, Go or Python, etc.

So here is a `tiny tool`, which helps me scrap my bookmarked courses' **meta data** (Author, Course Link, Length, etc.) and
store in a more convenient place like `Airtable`.

## Rationale 💡

I have near 35 courses `bookmarked`, so I decided it will be much more convenient (and obviously more fun) to write a few scripts for that.

## Tooling  🛠️

All the magic is done with `Puppeeteer`, which goes through the **Sign in** process, finds the right page and fetches the needed meta data.
Next phase is writing down this information into `Airtable` page with a help of [Airtable.js](https://github.com/Airtable/airtable.js) and voilà.
If the `Airtable.js` documentation does not look very **comprehensive**, a lot more **useful** docs can be found at https://airtable.com/api 

## Screencast  💻

![fm-favs-scrapper-demo](https://user-images.githubusercontent.com/6503508/150685892-6b8b4bd8-631c-420f-b223-7be95bcb8f63.gif)

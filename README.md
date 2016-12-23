Asciiz
====

The purpose of this ReactJS based site is to sell ascii faces (e.g. `¯_(ツ)_/¯`), with font choices. It will allow to browse the inventory.

Before beginning, read the instructions.

BONUS points are you chance to stand-out, but it is more critical to complete the basis.

Features
----

- A grid displays ascii faces.
- each product has :
  - "size”: px font-size. Display it accordingly in grid.
  - "price”: dollar price with 2 precision digits.
  - "date”: when it was added. BONUS: Dates should be displayed in days / week (eg. “yesterday”, “5 days ago") unless they are older than 1 month, fall back to regular date.
- show “End of faces” if reach the end of list.
- An option to sort by "size", "price" or "id" in ascending order.
- Repeat the ad in header every 10 faces
- BONUS: the product grid should automatically load more items as you scroll down.
- BONUS: an animated "loading..." message before grid is populated.
- BONUS: Pre-emptively fetch the next batch of faces in the background, without actually showing until they comes into scroll view.
- BOUNS: Make sure an ad never repeats in catalogue.


API
----

- Query looks like this: `/api/products`
- Response is JSON.
- You have `limit` parameter, eg: `/api/products?limit=50` and `skip` eg: `/api/products?limit=20&skip=100` (returns 20 face starting from the 100th).
- You have `sort` parameter, eg: `/api/products?sort=XXX`. When XXX can be: `price`, `size` and `id`.


* To start, use `npm start`. The server will look for any files you add to the `static/` directory. Do NOT touch ./lib


* You can use 3rd party modules, but keep it ReactJS.


* When finished, send `amit@qualicode.co` an email and tell him us what you’ve accomplished.

* Use clean and easy to read code, structural and maintainable.

* UI design skill are not important.

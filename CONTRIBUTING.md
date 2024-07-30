## How to contribute related articles?

### If JSON file exists

Visit [https://github.com/SeaQL/rustacean.info/edit/main/related-articles/CRATE_ID.json](https://github.com/SeaQL/rustacean.info/edit/main/related-articles/CRATE_ID.json) and replace the `CRATE_ID` with your desire crate ID. If the file exists, you can simply edit the JSON file and add more related articles into the JSON array.

### If JSON file does not exist

If the above edit link shows "404 - page not found", then please create a new file with crate ID as the file name.

Visit [https://github.com/SeaQL/rustacean.info/new/main/related-articles](https://github.com/SeaQL/rustacean.info/new/main/related-articles), and name the file as `CRATE_ID.json`.

Here is the sample JSON for your reference:

```json
[
    {
        "title": "This Week in Rust 556",
        "link": "https://this-week-in-rust.org/blog/2024/07/17/this-week-in-rust-556/"
    },
    {
        "title": "This Week in Rust 555",
        "link": "https://this-week-in-rust.org/blog/2024/07/10/this-week-in-rust-555/"
    }
]
```

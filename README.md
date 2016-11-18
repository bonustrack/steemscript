# Steem Script
An Open JSON Standard for Trusted Workflows

### Account json_metadata
```json
{
    "profile": {
        "name": "Ned Scott",
        "about": "CEO and Co-founder at Steemit",
        "website": "https://steem.io/",
        "cover_image": "https://img.busy6.com/@ned/cover",
        "profile_image": "https://img.busy6.com/@ned",
        "location": "New York",
        "gender": "male",
        "email": "ned@steem.io",
        "birthday": "12/31/1999",
        "timezone": "-5",
        "locale": "en_US",
        "languages": ["en"],
        "featured_post": "the-first-phase-of-the-steem-faq-and-wikee-consolidation-of-knowledge"
    },
    "dns": {"records":[["@","CNAME","steem.io"]]}}
}
```
## Account Guidelines

### Profile
- `name`: max. length 20 chars.
- `about`: max. length 160 chars.
- `location`: max. length 30 chars.
- `website`: valid `https://` URL with max. length 100 chars.
- `profile_image`: image URL, preferably square-cropped with a minimum size of 230 x 230 pixels.


### Comment json_metadata
```json
{
    "app_name": "steemit/1.23",
    "format": "html",
    "tags": ["steemit", "steem"],
    "users": ["ned", "dan"],
    "images": ["https://img.busy6.com/@ned"],
    "videos": ["https://www.youtube.com/watch?v=rkQ7b-u8_6g", "https://www.youtube.com/watch?v=H399YZ0pv0o"],
    "status": "archived",
    "canonical": "http://blog.steem.io/steem/@ned/the-first-phase-of-the-steem-faq-and-wikee-consolidation-of-knowledge"
}
```

# Steem Script
An Open JSON Standard for Trusted Workflows

https://gist.github.com/adcpm/021525e2304a55f31637e60db3c87532

### Account json_metadata
```json
{
    "version": "0.0.1",
    "dns": {"records":[["@","CNAME","steem.io"]]}},
    "profile": {
        "name": "Ned Scott",
        "email": "ned@steem.io",
        "birthday": "12/31/1999",
        "gender": "male",
        "about": "CEO and Co-founder at Steemit",
        "location": "New York",
        "timezone": "-5",
        "locale": "en_US",
        "languages": ["en"],
        "website": "https://steem.io/",
        "cover_image": "https://img.busy6.com/@ned/cover",
        "profile_image": "https://img.busy6.com/@ned",
        "featured_post": "the-first-phase-of-the-steem-faq-and-wikee-consolidation-of-knowledge"
    }
}
```

### Comment json_metadata
```json
{
    "version": "0.0.1",
    "format": "html",
    "app_name": "steemit/1.23",
    "tags": ["steemit", "steem"],
    "users": ["ned", "dan"],
    "images": ["https://img.busy6.com/@ned"],
    "videos": ["https://www.youtube.com/watch?v=rkQ7b-u8_6g", "https://www.youtube.com/watch?v=H399YZ0pv0o"],
    "status": "archived",
    "canonical": "http://blog.steem.io/steem/@ned/the-first-phase-of-the-steem-faq-and-wikee-consolidation-of-knowledge"
}
```

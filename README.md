# json-wa-bot
# Get started
- Install modules
```
npm install
```
- start bot & scan QR
```
node emperor.adji
```
# EXAMPLE
- sending text
```json
{
            "commands": [
                {
                    "contains": [],
                    "exact": ["/start"],
                    "pattern": []
                }
            ],
            "text": [
                {
                    "text": "Hello there!",
                    "delay": 1500,
                    "isQuoted": true
                }
            ]
}
```
# Media
```
{
            "commands": [
                {
                    "contains": [],
                    "exact": ["/image"],
                    "pattern": []
                }
            ],
            "text": [],
            "media": [
                {
                    "type": "image",
                    "url": "https://th.bing.com/th/id/OIP.-kHo2Va5aIrPOKKZaqqFXQHaEK?rs=1&pid=ImgDetMain",
                    "caption": "This is an image",
                    "isQuoted": true
                }
            ]
 }

"media": [
    {
        "type": "video",
        "url": "https://example.com/video.mp4",
        "caption": "This is a video"
    }
]

"media": [
    {
        "type": "audio",
        "url": "https://example.com/audio.mp3",
        "mimetype": "audio/mp3"
    }
]

"media": [
    {
        "type": "document",
        "url": "https://example.com/document.pdf",
        "mimetype": "application/pdf",
        "fileName": "document.pdf"
    }
]
```

# ENDING < < <

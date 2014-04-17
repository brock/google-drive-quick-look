# Google Drive Quick Look plugin

Google Drive stores your contents as links to Google Drive. They are json files with the following format:

```
{
  "url": "https://docs.google.com/...",
  "resource_id": "document:abc123..."
}

```

This Quick Look plugin currently shows the json text, but I'd like to be able to render an HTML preview (or CSV, or Pages/Doc, etc).


See the discussion here:  
https://productforums.google.com/forum/#!msg/drive/aHASu_npFMk/NcijNJtPCwgJ

Following instructions from here:  
http://blog.10to1.be/cocoa/2012/01/27/creating-a-quick-look-plugin/

And copy/pasting from here:  
https://github.com/fousa/thong/blob/master/thong/GeneratePreviewForURL.m


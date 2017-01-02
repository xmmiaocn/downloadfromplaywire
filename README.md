# downloadfromplaywire
STEPS IN CASE YOU WANT TO SKIP THE VIDEO:

1) Use 'Inspect Element' or 'View Page Source' on the match highlights page
2) Copy content of 'data-config' attribute (which is a partial URL)
3) Add "http:" to the above copied content (which is a zeus.json file) to make it a complete URL and open the URL in a new tab
4) Copy the content of the opened link (which is in JSON format)
5) Open JSON beautifier (codebeautify.org/jsonviewer) and paste the above copied JSON content
6) In the beautified section, search for manifest. Copy the whole String (i.e. character content for non-programming world people usually inside inverted commas) containing the manifest sequence, which is another URL.
7) Open this URL in a new tab. You will see XML content. Copy the baseURL content
8) Open a new tab, Pase the baseURL content and append after adding a slash, the file-name of the file (whose name should be self-explanatory), also present in the opened XML, you wish to download. Press Enter. You can now watch the video.

source:https://www.youtube.com/watch?v=LWRAtcTPz2o

playwiresite:http://www.fullmatchesandshows.com/

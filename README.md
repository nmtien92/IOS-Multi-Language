# IOS-Multi-Language
IOS Multi Language: Automatically detect language that iOS device, faster and easier to use than the traditional way.

<h2>Installation</h2> 
<a href="https://www.dropbox.com/s/f6e01zx4yr35i67/IOS%20Multi%20Language.zip?dl=0">Download example project</a><br>
Config File: "Languages.json", add more languages and key and values of string. <br>
<a href="https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes">List of ISO 639-1 codes</a>
<pre>
<code>
{
    "created": "10/18/15",
    "author": "nmtien92",
    "default": "en",
    "languages": {
        "en": {
            "hello_world": "Hello World",
            "app_name": "Maps",
            "test": "nmtien92@outlook.com"
        },
        "vi": {
            "hello_world": "Xin chào",
            "app_name": "Bản đồ"
        },
        "fr": {
            "hello_world": "Bonjour",
            "app_name": "Carte"
        },
        "jp": {
            "hello_world": "こんにちは",
            "app_name": "マップ"
        }
    }
}
</code>
</pre>

add more files into project: (Utils.h, Utils.m, R.h, R.m)

<h2>Usage</h2>
<pre>
<code>
R *mContext = [[R alloc] init];
NSString *app_name = [mContext getString:@"test"];
NSLog(@"%@", app_name);
</code>
</pre>

<h2>Contacts</h2>
<pre>
<code>
if you have any problems, please contact email: nmtien92@outlook.com
</code>
</pre>

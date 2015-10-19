# IOS-Multi-Language
IOS Multi Language: Automatically detect language that iOS device, faster and easier to use than the traditional way.
<h2>Usage</h2>

<pre>
<code>
Config File: "Languages.json"
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

<pre>
<code>
R *mContext = [[R alloc] init];
NSString *app_name = [mContext getString:@"test"];
NSLog(@"%@", app_name);
</code>
</pre>

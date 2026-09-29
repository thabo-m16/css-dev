Core Components of CSS Notation
- Selector: Points to the HTML element you want to style (e.g., h1, .class, #id).
- Declaration Block: Surrounded by curly braces { }, it holds one or more individual style declarations.
- Property: The style attribute you want to change, such as color or font-size.- Value: The specific setting assigned to the property, separated from the property by a colon :.
- Semicolon (;): Used to separate individual declarations from one another inside the block.

e.g body{
    color: red;
}

All properties and its values: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides

The <link> tag contains:
Attribute                                 Purpose              Common Values 
rel (Required)Specifies the relationship 
between the current page and the linked resource.                                                        "stylesheet", "icon", "preload", "canonical"hrefSpecifies the URL/path to the external file."styles.css", "https://example.com"typeDefines the media type of the linked content."text/css", "image/png"mediaSpecifies which device or media query the resource is optimized for."print", "(max-width: 600px)"
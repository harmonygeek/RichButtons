# Wearable Reply

## Introduction:
'RichButtons' is a set of button styles for openharmony applications. All of the styles are made of XML.

## Usage Instructions:

#Blue
            <Button
                ohos:background_element="$graphic:rb__blue_button"               
                ohos:text="RbButton.Blue"/>
#Purple
            <Button               
                ohos:background_element="$graphic:rb__button_purple"
                ohos:text="RbButton.purpal"/>
#Green
            <Button                
                ohos:background_element="$graphic:rb__button_green"
                ohos:text="RbButton.green"/>
#Yellow
            <Button
                ohos:background_element="$graphic:rb__button_yellow"
                ohos:text="RbButton.yellow"/>
#Red
            <Button                
                ohos:background_element="$graphic:rb__button_red"
                ohos:text="RbButton.red"/>

## Installation instructions:

```
Method 1:
    Generate the .har package through the library and add the .har package to the libs folder.
    Add the following code to the entry gradle:
        implementation fileTree  (dir: 'libs', include: ['*.jar', '*.har'])

Method 2:
    allprojects{
        repositories{
            mavenCentral()
        }
    }
implementation project(path: ':richbutton')
```

## License

    Copyright (c) 2013 Soichiro Kashima.

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.

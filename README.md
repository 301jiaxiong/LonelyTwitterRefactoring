# LonelyTwitterRefactoring

Fixing ：

1.
In the main.xml, giving warning No label views point to this text field
with an 'android:labelFor="@+id/body"'attributeat 
Therefore at line 30 add a android:labelFor="@id/body".

2.
In the AndriodMainfest.xml, warning at line 7 <uses-sdk android:minSdkVersion="17" />
is not used. It is always being overriden. Deleted that line.

3.
In the main.xml, warning This text field does not specify an 'inputType' or a 'hint'
Added android:inputType="text" at the Line 31.

4.
In the strings.xml,<string name="invalid_tweet">Invalid tweet</string>
<string name="important_identifier">*</string> not used. Deleted.

5.
In the main.xml,warning line 16 using the layout_height =0 to get better performance
Therefore, changed to 0dp.

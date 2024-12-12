# How-to-Customize-Content-Spacing-in-.NET-MAUI-CheckBox.
This repository contains a sample explaining how to Customize Content Spacing in .NET MAUI CheckBox

### ContentSpacing support in .NET MAUI CheckBox

The `ContentSpacing` feature in CheckBox control allows for flexible adjustment of the space between the control's visual element and its associated label text.

The following code example illustrate how to set ContentSpacing in SfCheckBox.

### XAML

```
    <syncfusion:SfCheckBox Text="Check Box" ContentSpacing="25"/>

```

### C#

```
    SfCheckBox  sfCheckBox  = new SfCheckBox();
    sfCheckBox.Text = "Check Box";
    sfCheckBox.ContentSpacing = 25;
```
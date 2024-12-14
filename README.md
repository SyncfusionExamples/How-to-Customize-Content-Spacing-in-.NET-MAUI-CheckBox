# How-to-Customize-Content-Spacing-in-.NET-MAUI-CheckBox.
This repository contains a sample explaining how to Customize Content Spacing in .NET MAUI CheckBox

### ContentSpacing support in .NET MAUI CheckBox

The `ContentSpacing` feature in CheckBox control allows for flexible adjustment of the space between the control's visual element and its associated label text.

The following code example illustrate how to set ContentSpacing in SfCheckBox.

### XAML

```
    <StackLayout Padding="20">
        <syncfusion:SfCheckBox Text="I accept the terms and conditions"
              ContentSpacing="15"
              IsChecked="True" 
              HorizontalOptions="Start"/>

        <syncfusion:SfCheckBox Text="Subscribe to newsletter"
              ContentSpacing="15"
              IsChecked="False" 
              HorizontalOptions="Start"/>

        <syncfusion:SfCheckBox Text="Enable email notifications"
              ContentSpacing="15" 
              IsChecked="True" 
              HorizontalOptions="Start"/>

        <syncfusion:SfCheckBox Text="Remember me on this device"
              ContentSpacing="15" 
              IsChecked="False" 
              HorizontalOptions="Start"/>

        <syncfusion:SfCheckBox Text="Allow location access"
              ContentSpacing="15" 
              IsChecked="True" 
              HorizontalOptions="Start"/>
    </StackLayout>
```

### C#

```
    SfCheckBox  sfCheckBox  = new SfCheckBox();
    sfCheckBox.Text = "I accept the terms and conditions";
    sfCheckBox.ContentSpacing = 25;
```
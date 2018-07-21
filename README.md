# ExpandableView control for Xamarin Forms

## Setup
* Available on NuGet: [ExpandableView](http://www.nuget.org/packages/ExpandableView) [![NuGet](https://img.shields.io/nuget/v/ExpandableView.svg?label=NuGet)](https://www.nuget.org/packages/ExpandableView)
* Add nuget package to your Xamarin.Forms .netStandard/PCL project and to your platform-specific projects

|Platform|Version|
| ------------------- | ------------------- |
|Xamarin.iOS|8.0+|
|Xamarin.Android|15+|
|Windows 10 UWP|10.0.10240+|

## ExpandableView
This plugin provides opportunity to create expandable views

![Sample GIF](https://media.giphy.com/media/39hpHTXx2KF2s6faYg/giphy.gif)

**XAML:**
```xml

<expandable:ExpandableView>
    <expandable:ExpandableView.PrimaryView>
        //{YOUR MAIN VIEW HERE}
        </ContentView>
    </expandable:ExpandableView.PrimaryView>
    <expandable:ExpandableView.SecondaryViewTemplate>
        <DataTemplate>
            //{YOUR DROP-DOWN MENU TEMPLATE HERE} you can use DataTemplateSelector too
        </DataTemplate>
    </expandable:ExpandableView.SecondaryViewTemplate>
</expandable:ExpandableView>
```

**C#:**

The sample you can find here https://github.com/AndreiMisiukevich/ExpandableView/blob/master/ExpandableViewSample/App.cs

Check source code for more info, or 🇧🇾 ***just ask me =)*** 🇧🇾

## License
The MIT License (MIT) see [License file](LICENSE)

## Contribution
Feel free to create issues and PRs 😃

# How-to-add-the-fonticon-into-.NET-MAUI-RadialMenu
This section explains how to add the fonticon into .NET MAUI RadialMenu

To add a custom font icon to a .NET MAUI RadialMenu, follow these steps:

1. Add the custom font file (.ttf) to the font folder of your .NET MAUI project.

2. In the XAML code, reference the custom font family for the RadialMenu and its items using the FontFamily property.
XAML

**XAML**

```
  <syncfusion:SfRadialMenu 
               CenterButtonBackFontFamily="MauiMaterialAssets"
               CenterButtonBackFontSize="28"
               CenterButtonBackText="&#xe72d;"
               CenterButtonFontFamily="MauiMaterialAssets"
               CenterButtonFontSize="28"
               CenterButtonText="&#xe710;">
       <syncfusion:SfRadialMenu.Items>
           <syncfusion:SfRadialMenuItem FontFamily="MauiMaterialAssets"
                       FontSize="20"
                       Text="&#xe72e;"/>
           <syncfusion:SfRadialMenuItem  FontFamily="MauiMaterialAssets"
                       FontSize="20"
                       Text="&#xe744;"/>
           <syncfusion:SfRadialMenuItem FontFamily="MauiMaterialAssets"
                       FontSize="20"
                       Text="&#xe745;"/>
           <syncfusion:SfRadialMenuItem FontFamily="MauiMaterialAssets"
                       FontSize="20"
                       Text="&#xe73b;"/>
           <syncfusion:SfRadialMenuItem FontFamily="MauiMaterialAssets"
                       FontSize="20"
                       Text="&#xe762;"/>
       </syncfusion:SfRadialMenu.Items>
   </syncfusion:SfRadialMenu>
```

## How to run this application?

To run this application, you need to first clone the How-to-render-a-custom-content-to-.NET-MAUI-Carousel repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.


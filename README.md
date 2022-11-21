<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/568798846/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1128957)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Form Layout for Blazor – Collapsible groups 

This example demonstrates how to use the [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout) component to implement collapsible groups.

![Collapsible groups with validation](/form-layout-collapsible-groups.png)

Use the [Expanded](http://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutGroup.Expanded) property to change the expand state and handle the [ExpandedChanged](http://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutGroup.ExpandedChanged) event to react to state changes. To allow users to expand and collapse groups from the UI, specify the [ExpandButtonDisplayMode](http://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutGroup.ExpandButtonDisplayMode) property. You can also specify the [ExpandButtonCssClass](http://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutGroup.ExpandButtonIconCssClass) and [CollapseButtonCssClass](http://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutGroup.CollapseButtonIconCssClass) properties to apply custom icons to the expand button. 

In this example, a user can expand and collapse groups to enter editor values by section. If validation fails on the **Submit** button click, the Form Layout component opens all groups. 

## Files to Review

[Index.razor](/CS/CollapsibleGroups/Pages/Index.razor)

## Documentation

[DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout) 

## More Examples 

[Tabbed Wizard](https://github.com/DevExpress-Examples/Form-Layout-for-Blazor-Tabbed-Wizard) 

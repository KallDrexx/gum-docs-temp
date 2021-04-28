---
title: IDataUi
parent: Gum Code Reference
---

# WpfDataUi.IDataUi

## Introduction

The IDataUi is an interface that is used by the [WpfDataUi.DataUiGrid](https://github.com/KallDrexx/gum-docs-temp/tree/34f8cf390aa0e8acda804733eaad97a22b8c533b/pages/programming/WpfDataUi.DataUiGrid)\(WpfDataUi.DataUiGrid\) class to display data. This interface must be implemented by any controls which are used in the [WpfDataUi.DataUiGrid](https://github.com/KallDrexx/gum-docs-temp/tree/34f8cf390aa0e8acda804733eaad97a22b8c533b/pages/programming/WpfDataUi.DataUiGrid)\(WpfDataUi.DataUiGrid\). The WpfDataUi library contains a number of built-in controls which implement the IDataUi interface, but it can easily be extended to support more controls.

## Creating IDataUi Controls

To create a custom display:

1. Add a new User Control \(WPF\)
2. In the codebehind file, implement the IDataUi interface
3. This newly-created control can be used in a WpfDataUi grid by assigning the [WpfDataUi.DataTypes.InstanceMember.PreferredDisplayer](https://github.com/KallDrexx/gum-docs-temp/tree/34f8cf390aa0e8acda804733eaad97a22b8c533b/pages/programming/WpfDataUi.DataTypes.InstanceMember.PreferredDisplayer) property.


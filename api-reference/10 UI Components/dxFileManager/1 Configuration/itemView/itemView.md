---
id: dxFileManager.Options.itemView
type: Object
default: null
---
---
##### shortDescription
Configures the file and folder view.

---

[note] Set the [itemView.mode](/api-reference/10%20UI%20Widgets/dxFileManager/1%20Configuration/itemView/mode.md '/Documentation/ApiReference/UI_Components/dxFileManager/Configuration/itemView/#mode') property to **details** to configure [columns](/api-reference/10%20UI%20Widgets/dxFileManager/1%20Configuration/itemView/details/columns.md '/Documentation/ApiReference/UI_Components/dxFileManager/Configuration/itemView/details/columns/') in the UI component.

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/FileManager/UICustomization/"
}

![DevExtreme File Manager - Item View](/images/FileManager/item-view.png)

---

##### jQuery

    <!--JavaScript-->
    $(function () {
        $("#file-manager").dxFileManager({
            itemView: {
                mode: "details",
                showFolders: false,
                showParentFolder: false
            }
            // ...
        });
    });

---

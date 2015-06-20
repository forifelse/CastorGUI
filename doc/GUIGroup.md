##new [GUIGroup](#)(id, options, guimanager)
Creates a new GUIGroup

####Parameters
Name | Type | Description
---|---|---
**id** | string | The id and name element
**options** | json | Options of element
**guimanager** | GUIManager | The gui manager
---

##Options

* **x**: position left of group (in pixel)
* **y**: position top of group (in pixel)

##Methods

###add(GUIElement) → void
add element in the GUIGroup

###setVisible(bool) → void
Set this GUI element to visible or invisible

###isVisible(bool, fade) → void
Returns element if is visible or no

###dispose() → void
Dispose the GUIGroup, and delete all elements of group.
# Function: <code>subsys_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f067)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
```
```
In drivers/base/bus.c (ffffffff81b366bc)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81b3b475)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86867)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
```
```
In drivers/base/bus.c (ffffffff81b8e0dc)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81b92fc5)
Location: drivers/base/base.h:70
Inline: True
Inline callers:
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

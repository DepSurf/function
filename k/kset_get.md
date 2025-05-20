# Function: <code>kset_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec0b2)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff815497c4)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_driver
```
```
In drivers/base/class.c (ffffffff8154cdc2)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff814323b0)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff8159b9a5)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff8159ebb2)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e620)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff815c9f05)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff815cd172)
Location: include/linux/kobject.h:187
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815dec3f)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff815e1c5c)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff818ee8b4)
Location: include/linux/kobject.h:189
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81645c6f)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff81648dcc)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81974b74)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816810c5)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816843a2)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff819d1184)
Location: include/linux/kobject.h:194
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a0b55)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816a4062)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a0a6e4)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d9a95)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816dcf92)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a7a045)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fda45)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff81701042)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81ab13a5)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eb17d)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817b7800)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817bb51d)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160fa99)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817cc520)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817d010d)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f31d9)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff817afe95)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff817b3b22)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff816603a9)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff81839155)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff8183d002)
Location: include/linux/kobject.h:211
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779d8a)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/base/bus.c (ffffffff8197b77f)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff8197fbec)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae883f)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/class.c (ffffffff81aed50c)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff82022dca)
Location: include/linux/kobject.h:191
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b35f96)
Location: include/linux/kobject.h:184
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_to_subsys
```
```
In drivers/base/class.c (ffffffff81b3b206)
Location: include/linux/kobject.h:184
Inline: True
Inline callers:
  - drivers/base/class.c:class_to_subsys
```
```
In lib/kobject.c (ffffffff820a2e3a)
Location: include/linux/kobject.h:184
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
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
In drivers/base/bus.c (ffffffff81b8d9b6)
Location: include/linux/kobject.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_to_subsys
```
```
In drivers/base/class.c (ffffffff81b92d56)
Location: include/linux/kobject.h:186
Inline: True
Inline callers:
  - drivers/base/class.c:class_to_subsys
```
```
In lib/kobject.c (ffffffff8217aeba)
Location: include/linux/kobject.h:186
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e86dc)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffff8000108ec88c)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffff800010d8ae2c)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6ae0)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (c09da714)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (c0e85a80)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097edfc)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (c00000000098420c)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (c000000000eccc38)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057c9d8)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffe00057fb86)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffe0008b47f2)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3235)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816c6832)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a501f5)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e4e5)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816a1a92)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81a0d2f5)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1705)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff816f4d02)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81abc5e5)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170bf45)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/class.c (ffffffff8170f592)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
```
```
In lib/kobject.c (ffffffff81ac8a65)
Location: include/linux/kobject.h:212
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>

## Differences

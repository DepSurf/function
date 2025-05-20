# Function: <code>of_node_check_flag</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/spi/spi.c (ffff8000109c422c)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6bd4)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/of/base.c (ffff800010b6a140)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
```
```
In drivers/of/platform.c (ffff800010b6d818)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (ffff800010b70990)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:__of_detach_node
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/resolver.c (ffff800010b76ba4)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (ffff800010b7795c)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In lib/vsprintf.c (ffff800010d95aa8)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In drivers/spi/spi.c (c0ab0f34)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c0b96d88)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/of/base.c (c0c4d0a0)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
```
```
In drivers/of/platform.c (c0c50674)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (c0c52fec)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:__of_detach_node
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/resolver.c (c0c58ea0)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (c0c598c0)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:add_changeset_property
```
```
In lib/vsprintf.c (c0e92b94)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In drivers/spi/spi.c (c000000000a88c20)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99b60)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/of/base.c (c000000000c428d0)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
```
```
In drivers/of/platform.c (c000000000c48060)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (c000000000c4c16c)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:__of_detach_node
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/resolver.c (c000000000c554bc)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (c000000000c5664c)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In lib/vsprintf.c (c000000000edad80)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In drivers/spi/spi.c (ffffffe000618634)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc7b4)
Location: include/linux/of.h:188
Inline: True
```
```
In drivers/of/base.c (ffffffe00071f306)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
```
```
In drivers/of/platform.c (ffffffe000722414)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (ffffffe000724920)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:__of_detach_node
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/resolver.c (ffffffe000729f48)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (ffffffe00072af32)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In lib/vsprintf.c (ffffffe0008bf3c4)
Location: include/linux/of.h:188
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
</details>
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

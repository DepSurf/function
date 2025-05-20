# Function: <code>of_find_node_with_property</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device_node *of_find_node_with_property(struct device_node *from, const char *prop_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69af8)
Location: drivers/of/base.c:1084
Inline: False
Direct callers:
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
```
**Symbols:**

```
ffff800010b69af8-ffff800010b69c44: of_find_node_with_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_node_with_property(struct device_node *from, const char *prop_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4cf00)
Location: drivers/of/base.c:1084
Inline: False
Direct callers:
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
```
**Symbols:**

```
c0c4cf00-c0c4cfe8: of_find_node_with_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_node_with_property(struct device_node *from, const char *prop_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c42470)
Location: drivers/of/base.c:1084
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/iommu.c:__machine_initcall_pseries_find_existing_ddw_windows
  - arch/powerpc/platforms/pseries/iommu.c:__machine_initcall_pseries_find_existing_ddw_windows
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
```
**Symbols:**

```
c000000000c42470-c000000000c427a0: of_find_node_with_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_node_with_property(struct device_node *from, const char *prop_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f184)
Location: drivers/of/base.c:1084
Inline: False
Direct callers:
  - drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy
```
**Symbols:**

```
ffffffe00071f184-ffffffe00071f256: of_find_node_with_property (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>

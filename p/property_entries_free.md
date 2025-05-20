# Function: <code>property_entries_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6580)
Location: drivers/base/property.c:791
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff815e6580-ffffffff815e65b7: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d850)
Location: drivers/base/property.c:832
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff8164d850-ffffffff8164d887: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689240)
Location: drivers/base/property.c:892
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff81689240-ffffffff81689277: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa582)
Location: drivers/base/swnode.c:414
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff816aa4c0-ffffffff816aa4f7: property_entries_free.part.7 (STB_LOCAL)
ffffffff816aa500-ffffffff816aa516: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e41a0)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff816e3f70-ffffffff816e3fa7: property_entries_free.part.0 (STB_LOCAL)
ffffffff816e3fb0-ffffffff816e3fc6: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81708230)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff81708000-ffffffff81708037: property_entries_free.part.0 (STB_LOCAL)
ffffffff81708040-ffffffff81708056: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2f9d)
Location: drivers/base/swnode.c:333
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff817c30b0-ffffffff817c30ed: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7dde)
Location: drivers/base/swnode.c:333
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff817d7ef0-ffffffff817d7f2d: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc252)
Location: drivers/base/swnode.c:347
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff817bb9b0-ffffffff817bb9ed: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846542)
Location: drivers/base/swnode.c:349
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff81845cf0-ffffffff81845d2d: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a6d7)
Location: drivers/base/swnode.c:349
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81989cc0-ffffffff81989cfd: property_entries_free.part.0 (STB_LOCAL)
ffffffff8198a090-ffffffff8198a0d9: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af9b17)
Location: drivers/base/swnode.c:349
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81af9030-ffffffff81af906d: property_entries_free.part.0 (STB_LOCAL)
ffffffff81af9080-ffffffff81af90c9: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b480c7)
Location: drivers/base/swnode.c:349
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81b475a0-ffffffff81b475dd: property_entries_free.part.0 (STB_LOCAL)
ffffffff81b475f0-ffffffff81b47639: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba04b5)
Location: drivers/base/swnode.c:349
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81b9f930-ffffffff81b9f96d: property_entries_free.part.0 (STB_LOCAL)
ffffffff81b9f980-ffffffff81b9f9c9: property_entries_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5d2c)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffff8000108f5b20-ffff8000108f5b6c: property_entries_free.part.0 (STB_LOCAL)
ffff8000108f5b70-ffff8000108f5ba0: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c09e2248)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
c09e2044-c09e208c: property_entries_free.part.0 (STB_LOCAL)
c09e208c-c09e20b0: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c000000000990d50)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
c0000000009909d0-c000000000990a4c: property_entries_free.part.0 (STB_LOCAL)
c000000000990a50-c000000000990a6c: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586e76)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffe000586c86-ffffffe000586cce: property_entries_free.part.0 (STB_LOCAL)
ffffffe000586cce-ffffffe000586cfa: property_entries_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd980)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff816cd750-ffffffff816cd787: property_entries_free.part.0 (STB_LOCAL)
ffffffff816cd790-ffffffff816cd7a6: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8cb0)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff816a8a80-ffffffff816a8ab7: property_entries_free.part.0 (STB_LOCAL)
ffffffff816a8ac0-ffffffff816a8ad6: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fbef0)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff816fbcc0-ffffffff816fbcf7: property_entries_free.part.0 (STB_LOCAL)
ffffffff816fbd00-ffffffff816fbd16: property_entries_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void property_entries_free(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff817169d0)
Location: drivers/base/swnode.c:456
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
```
**Symbols:**

```
ffffffff817167a0-ffffffff817167d7: property_entries_free.part.0 (STB_LOCAL)
ffffffff817167e0-ffffffff817167f6: property_entries_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

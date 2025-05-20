# Function: <code>fwnode_get_next_parent_dev</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d66e0)
Location: drivers/base/property.c:628
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff817d66e0-ffffffff817d67b2: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817ba1a0)
Location: drivers/base/property.c:628
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff817ba1a0-ffffffff817ba272: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843e00)
Location: drivers/base/property.c:628
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81843e00-ffffffff81843ed2: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987ee0)
Location: drivers/base/property.c:627
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81987ee0-ffffffff81988008: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af6880)
Location: drivers/base/property.c:635
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81af6880-ffffffff81af69a8: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44b30)
Location: drivers/base/property.c:651
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81b44b30-ffffffff81b44c58: fwnode_get_next_parent_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *fwnode_get_next_parent_dev(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9cb80)
Location: drivers/base/property.c:715
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81b9cb80-ffffffff81b9cca8: fwnode_get_next_parent_dev (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

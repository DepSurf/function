# Function: <code>fw_devlink_create_devlink</code>

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
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ca030)
Location: drivers/base/core.c:1528
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff817ca030-ffffffff817ca0fd: fw_devlink_create_devlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1716
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff817ad850-ffffffff817ad953: fw_devlink_create_devlink (STB_LOCAL)
ffffffff81c00608-ffffffff81c00665: fw_devlink_create_devlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1731
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81836b40-ffffffff81836c41: fw_devlink_create_devlink (STB_LOCAL)
ffffffff81d02ba8-ffffffff81d02c5a: fw_devlink_create_devlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1743
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81978b80-ffffffff81978c7f: fw_devlink_create_devlink (STB_LOCAL)
ffffffff81ecb2f6-ffffffff81ecb3a0: fw_devlink_create_devlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae5490)
Location: drivers/base/core.c:2024
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81ae5490-ffffffff81ae5747: fw_devlink_create_devlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b33850)
Location: drivers/base/core.c:2026
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81b33850-ffffffff81b33b18: fw_devlink_create_devlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_devlink_create_devlink(struct device *con, struct fwnode_handle *sup_handle, struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8b190)
Location: drivers/base/core.c:2035
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81b8b190-ffffffff81b8b4a7: fw_devlink_create_devlink (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_link *link</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

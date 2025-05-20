# Function: <code>fwnode_is_ancestor_of</code>

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
bool fwnode_is_ancestor_of(struct fwnode_handle *test_ancestor, struct fwnode_handle *test_child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d67c0)
Location: drivers/base/property.c:698
Inline: False
```
**Symbols:**

```
ffffffff817d67c0-ffffffff817d68cd: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(struct fwnode_handle *test_ancestor, struct fwnode_handle *test_child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817ba280)
Location: drivers/base/property.c:698
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_link_device
```
**Symbols:**

```
ffffffff817ba280-ffffffff817ba38d: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(struct fwnode_handle *test_ancestor, struct fwnode_handle *test_child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843ee0)
Location: drivers/base/property.c:699
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81843ee0-ffffffff81843fed: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(struct fwnode_handle *ancestor, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81988010)
Location: drivers/base/property.c:697
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81988010-ffffffff8198812a: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(struct fwnode_handle *ancestor, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af69c0)
Location: drivers/base/property.c:705
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81af69c0-ffffffff81af6ada: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(const struct fwnode_handle *ancestor, const struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44c70)
Location: drivers/base/property.c:721
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81b44c70-ffffffff81b44d81: fwnode_is_ancestor_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fwnode_is_ancestor_of(const struct fwnode_handle *ancestor, const struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9ccc0)
Location: drivers/base/property.c:785
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81b9ccc0-ffffffff81b9cdd1: fwnode_is_ancestor_of (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle *ancestor</code>
</li>
<li>
<b>Param added. </b>
<code>struct fwnode_handle *child</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle *test_ancestor</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle *test_child</code>
</li>
</ul>
</details>
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
<code>struct fwnode_handle *ancestor</code> ➡️ <code>const struct fwnode_handle *ancestor</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *child</code> ➡️ <code>const struct fwnode_handle *child</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

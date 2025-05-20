# Function: <code>internal_create_groups</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136fe35)
Location: fs/sysfs/group.c:178
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff8136fd70-ffffffff8136fe0c: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813881a5)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff813880e0-ffffffff8138817c: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d3145)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff813d3080-ffffffff813d3119: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4ea5)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff813e4de0-ffffffff813e4e79: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813ebaa5)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff813eb9e0-ffffffff813eba79: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d835)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff8143d770-ffffffff8143d809: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int internal_create_groups(struct kobject *kobj, int update, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8ac0)
Location: fs/sysfs/group.c:178
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff814b8ac0-ffffffff814b8b76: internal_create_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int internal_create_groups(struct kobject *kobj, int update, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81550150)
Location: fs/sysfs/group.c:178
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff81550150-ffffffff81550206: internal_create_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int internal_create_groups(struct kobject *kobj, int update, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587e50)
Location: fs/sysfs/group.c:182
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff81587e50-ffffffff81587f06: internal_create_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int internal_create_groups(struct kobject *kobj, int update, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0a10)
Location: fs/sysfs/group.c:182
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff815c0a10-ffffffff815c0ac6: internal_create_groups (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffff80001045842c)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffff800010458300-ffff8000104583c0: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (c061a4dc)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
c061a408-c061a498: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (c000000000572e10)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
c000000000572cb0-c000000000572dcc: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e9560)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffe0002e946a-ffffffe0002e9502: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff81380785)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff813806c0-ffffffff8138075c: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371215)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff81371150-ffffffff813711ec: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e255)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff8137e190-ffffffff8137e22c: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391e55)
Location: fs/sysfs/group.c:179
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - fs/sysfs/group.c:sysfs_update_groups
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff81391d90-ffffffff81391e2c: internal_create_groups.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

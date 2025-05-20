# Function: <code>remove_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d520)
Location: fs/sysfs/group.c:21
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:sysfs_remove_group
```
**Symbols:**

```
ffffffff8128d520-ffffffff8128d58a: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff812baba0)
Location: fs/sysfs/group.c:21
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812baba0-ffffffff812bac08: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d02d0)
Location: fs/sysfs/group.c:21
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812d02d0-ffffffff812d0338: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff812dd990)
Location: fs/sysfs/group.c:21
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812dd990-ffffffff812dd9f8: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813022c0)
Location: fs/sysfs/group.c:21
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813022c0-ffffffff81302328: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff813300f0)
Location: fs/sysfs/group.c:19
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813300f0-ffffffff81330158: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff81347490)
Location: fs/sysfs/group.c:19
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81347490-ffffffff813474f8: remove_files.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136f890)
Location: fs/sysfs/group.c:19
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136f890-ffffffff8136f8f8: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffff81387bf0)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81387bf0-ffffffff81387c58: remove_files.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d26a0)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813d26a0-ffffffff813d2703: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4400)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813e4400-ffffffff813e4463: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb000)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813eb000-ffffffff813eb063: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143cd90)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff8143cd90-ffffffff8143cdf3: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8560)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff814b8560-ffffffff814b85cf: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8154fb80)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff8154fb80-ffffffff8154fbef: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587850)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff81587850-ffffffff815878bf: remove_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0410)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff815c0410-ffffffff815c047f: remove_files (STB_LOCAL)
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
In fs/sysfs/group.c (ffff800010457d90)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff800010457d90-ffff800010457e10: remove_files.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_files(struct kernfs_node *parent, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c06198c0)
Location: fs/sysfs/group.c:20
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c06198c0-c0619948: remove_files (STB_LOCAL)
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
In fs/sysfs/group.c (c000000000572550)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c000000000572550-c00000000057261c: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffe0002e9012)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e9012-ffffffe0002e9072: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffff813801d0)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813801d0-ffffffff81380238: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffff81370c60)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81370c60-ffffffff81370cc8: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffff8137dca0)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137dca0-ffffffff8137dd08: remove_files.isra.0 (STB_LOCAL)
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
In fs/sysfs/group.c (ffffffff813918a0)
Location: fs/sysfs/group.c:20
Inline: True
Direct callers:
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813918a0-ffffffff81391908: remove_files.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>

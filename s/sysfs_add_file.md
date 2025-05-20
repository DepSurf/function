# Function: <code>sysfs_add_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sysfs_add_file(struct kernfs_node *parent, const struct attribute *attr, bool is_bin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128cb1a)
Location: fs/sysfs/file.c:309
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
Direct callers:
  - fs/sysfs/group.c:sysfs_merge_group
```
**Symbols:**

```
ffffffff8128cba0-ffffffff8128cbba: sysfs_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sysfs_add_file(struct kernfs_node *parent, const struct attribute *attr, bool is_bin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812ba1aa)
Location: fs/sysfs/file.c:315
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
Direct callers:
  - fs/sysfs/group.c:sysfs_merge_group
```
**Symbols:**

```
ffffffff812ba230-ffffffff812ba24a: sysfs_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sysfs_add_file(struct kernfs_node *parent, const struct attribute *attr, bool is_bin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf8da)
Location: fs/sysfs/file.c:315
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
Direct callers:
  - fs/sysfs/group.c:sysfs_merge_group
```
**Symbols:**

```
ffffffff812cf960-ffffffff812cf97a: sysfs_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_add_file(struct kernfs_node *parent, const struct attribute *attr, bool is_bin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dcffd)
Location: fs/sysfs/file.c:317
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
Direct callers:
  - fs/sysfs/group.c:sysfs_merge_group
```
**Symbols:**

```
ffffffff812dd080-ffffffff812dd09a: sysfs_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sysfs_add_file(struct kernfs_node *parent, const struct attribute *attr, bool is_bin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8130192d)
Location: fs/sysfs/file.c:317
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
Direct callers:
  - fs/sysfs/group.c:sysfs_merge_group
```
**Symbols:**

```
ffffffff813019b0-ffffffff813019ca: sysfs_add_file (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>

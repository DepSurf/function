# Function: <code>sysfs_get_tree</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff8136f640)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff8136f640-ffffffff8136f676: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff813879a0)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff813879a0-ffffffff813879d6: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff813d2660)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff813d2660-ffffffff813d2696: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff813e43c0)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff813e43c0-ffffffff813e43f6: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff813eafc0)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff813eafc0-ffffffff813eaff6: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/mount.c (ffffffff8143cd76)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff8143cd40-ffffffff8143cd8c: sysfs_get_tree (STB_LOCAL)
ffffffff81cc86be-ffffffff81cc86d9: sysfs_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/mount.c (0)
Location: fs/sysfs/mount.c:26
Inline: False
```
**Symbols:**

```
ffffffff814b83d0-ffffffff814b8426: sysfs_get_tree (STB_LOCAL)
ffffffff81e7b417-ffffffff81e7b432: sysfs_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/mount.c (0)
Location: fs/sysfs/mount.c:26
Inline: False
```
**Symbols:**

```
ffffffff8154f9d0-ffffffff8154fa26: sysfs_get_tree (STB_LOCAL)
ffffffff8206bc59-ffffffff8206bc74: sysfs_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/mount.c (ffffffff81587816)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff815877e0-ffffffff81587836: sysfs_get_tree (STB_LOCAL)
ffffffff820ebae7-ffffffff820ebb02: sysfs_get_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/sysfs/mount.c (ffffffff815c03d6)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff815c03a0-ffffffff815c03f6: sysfs_get_tree (STB_LOCAL)
ffffffff821c8d4b-ffffffff821c8d66: sysfs_get_tree.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffff800010457980)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffff800010457980-ffff8000104579d0: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (c0619878)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
c0619878-c06198c0: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (c000000000571e70)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
c000000000571e70-c000000000571ee4: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffe0002e8df0)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffe0002e8df0-ffffffe0002e8e36: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff8137ff80)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff8137ff80-ffffffff8137ffb6: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff81370a10)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff81370a10-ffffffff81370a46: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff8137da50)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff8137da50-ffffffff8137da86: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sysfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/mount.c (ffffffff81391550)
Location: fs/sysfs/mount.c:26
Inline: True
```
**Symbols:**

```
ffffffff81391550-ffffffff81391586: sysfs_get_tree (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

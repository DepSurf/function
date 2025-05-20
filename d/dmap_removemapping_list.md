# Function: <code>dmap_removemapping_list</code>

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
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149c730)
Location: fs/fuse/dax.c:250
Inline: False
```
**Symbols:**

```
ffffffff8149c730-ffffffff8149c83f: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a2760)
Location: fs/fuse/dax.c:250
Inline: False
```
**Symbols:**

```
ffffffff814a2760-ffffffff814a2870: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fa810)
Location: fs/fuse/dax.c:251
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff814fa810-ffffffff814fa920: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158ada0)
Location: fs/fuse/dax.c:251
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff8158ada0-ffffffff8158aec0: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631550)
Location: fs/fuse/dax.c:251
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff81631550-ffffffff81631670: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669790)
Location: fs/fuse/dax.c:251
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff81669790-ffffffff816698b0: dmap_removemapping_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmap_removemapping_list(struct inode *inode, unsigned int num, struct list_head *to_remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a3a90)
Location: fs/fuse/dax.c:251
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff816a3a90-ffffffff816a3bb0: dmap_removemapping_list (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

# Function: <code>fuse_dax_inode_cleanup</code>

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
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d1e0)
Location: fs/fuse/dax.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8149d1e0-ffffffff8149d226: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3100)
Location: fs/fuse/dax.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff814a3100-ffffffff814a3146: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:374
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81cd2395-ffffffff81cd23ac: fuse_dax_inode_cleanup.cold (STB_LOCAL)
ffffffff814fb020-ffffffff814fb1b7: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:374
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81e854c8-ffffffff81e854df: fuse_dax_inode_cleanup.cold (STB_LOCAL)
ffffffff8158b4f0-ffffffff8158b693: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631d30)
Location: fs/fuse/dax.c:374
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81631d30-ffffffff81631ee4: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669f70)
Location: fs/fuse/dax.c:374
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81669f70-ffffffff8166a124: fuse_dax_inode_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_dax_inode_cleanup(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a42b0)
Location: fs/fuse/dax.c:374
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff816a42b0-ffffffff816a4464: fuse_dax_inode_cleanup (STB_GLOBAL)
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

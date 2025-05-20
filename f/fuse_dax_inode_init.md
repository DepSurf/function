# Function: <code>fuse_dax_inode_init</code>

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
void fuse_dax_inode_init(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149e1c0)
Location: fs/fuse/dax.c:1336
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff8149e1c0-ffffffff8149e1f5: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a4190)
Location: fs/fuse/dax.c:1336
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff814a4190-ffffffff814a41c5: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fc230)
Location: fs/fuse/dax.c:1333
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff814fc230-ffffffff814fc265: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158c800)
Location: fs/fuse/dax.c:1354
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff8158c800-ffffffff8158c85f: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816330e0)
Location: fs/fuse/dax.c:1354
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff816330e0-ffffffff8163313f: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166b3d0)
Location: fs/fuse/dax.c:1354
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff8166b3d0-ffffffff8166b42f: fuse_dax_inode_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_dax_inode_init(struct inode *inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a5750)
Location: fs/fuse/dax.c:1353
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_init_file_inode
```
**Symbols:**

```
ffffffff816a5750-ffffffff816a57af: fuse_dax_inode_init (STB_GLOBAL)
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
<code>unsigned int flags</code>
</li>
</ul>
</details>
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

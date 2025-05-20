# Function: <code>fuse_dax_conn_alloc</code>

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
int fuse_dax_conn_alloc(struct fuse_conn *fc, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149e0a0)
Location: fs/fuse/dax.c:1288
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8149e0a0-ffffffff8149e126: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a4070)
Location: fs/fuse/dax.c:1288
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814a4070-ffffffff814a40f6: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fc110)
Location: fs/fuse/dax.c:1285
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814fc110-ffffffff814fc196: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, enum fuse_dax_mode dax_mode, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158c6a0)
Location: fs/fuse/dax.c:1282
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8158c6a0-ffffffff8158c74c: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, enum fuse_dax_mode dax_mode, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81632f60)
Location: fs/fuse/dax.c:1282
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81632f60-ffffffff8163300c: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, enum fuse_dax_mode dax_mode, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166b250)
Location: fs/fuse/dax.c:1282
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8166b250-ffffffff8166b2fc: fuse_dax_conn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_dax_conn_alloc(struct fuse_conn *fc, enum fuse_dax_mode dax_mode, struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a55a0)
Location: fs/fuse/dax.c:1281
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff816a55a0-ffffffff816a567f: fuse_dax_conn_alloc (STB_GLOBAL)
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
<code>enum fuse_dax_mode dax_mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, dax_dev</code> ➡️ <code>fc, dax_mode, dax_dev</code>
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

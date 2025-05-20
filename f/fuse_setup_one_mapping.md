# Function: <code>fuse_setup_one_mapping</code>

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
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149cf20)
Location: fs/fuse/dax.c:181
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_upgrade_dax_mapping
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff8149cf20-ffffffff8149d0d0: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a2f50)
Location: fs/fuse/dax.c:181
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff814a2f50-ffffffff814a30fb: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fae70)
Location: fs/fuse/dax.c:182
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff814fae70-ffffffff814fb01b: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158a880)
Location: fs/fuse/dax.c:182
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff8158a880-ffffffff8158aa40: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81630fd0)
Location: fs/fuse/dax.c:182
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff81630fd0-ffffffff81631190: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669200)
Location: fs/fuse/dax.c:182
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff81669200-ffffffff816693be: fuse_setup_one_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_setup_one_mapping(struct inode *inode, long unsigned int start_idx, struct fuse_dax_mapping *dmap, bool writable, bool upgrade);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a3500)
Location: fs/fuse/dax.c:182
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff816a3500-ffffffff816a36be: fuse_setup_one_mapping (STB_LOCAL)
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

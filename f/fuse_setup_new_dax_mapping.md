# Function: <code>fuse_setup_new_dax_mapping</code>

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
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d690)
Location: fs/fuse/dax.c:430
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff8149d690-ffffffff8149d8a7: fuse_setup_new_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a37e0)
Location: fs/fuse/dax.c:430
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff814a37e0-ffffffff814a3ad2: fuse_setup_new_dax_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:431
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff814fb840-ffffffff814fbb45: fuse_setup_new_dax_mapping (STB_LOCAL)
ffffffff81cd23ac-ffffffff81cd23c1: fuse_setup_new_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:431
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff8158bd30-ffffffff8158c066: fuse_setup_new_dax_mapping (STB_LOCAL)
ffffffff81e854df-ffffffff81e854f4: fuse_setup_new_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:431
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff81632570-ffffffff816328a9: fuse_setup_new_dax_mapping (STB_LOCAL)
ffffffff82072957-ffffffff8207296c: fuse_setup_new_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:431
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff8166a4c0-ffffffff8166a7f9: fuse_setup_new_dax_mapping (STB_LOCAL)
ffffffff820f25bb-ffffffff820f25d0: fuse_setup_new_dax_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fuse_setup_new_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:431
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff816a4800-ffffffff816a4b39: fuse_setup_new_dax_mapping (STB_LOCAL)
ffffffff821cf856-ffffffff821cf86b: fuse_setup_new_dax_mapping.cold (STB_LOCAL)
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

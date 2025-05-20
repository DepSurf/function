# Function: <code>fuse_dax_check_alignment</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1347
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff81bef7d2-ffffffff81bef7ea: fuse_dax_check_alignment.cold (STB_LOCAL)
ffffffff8149e200-ffffffff8149e229: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1347
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff81be187a-ffffffff81be1893: fuse_dax_check_alignment.cold (STB_LOCAL)
ffffffff814a41d0-ffffffff814a41ee: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1344
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff81cd241c-ffffffff81cd2435: fuse_dax_check_alignment.cold (STB_LOCAL)
ffffffff814fc270-ffffffff814fc28e: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1372
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff81e8554e-ffffffff81e85571: fuse_dax_check_alignment.cold (STB_LOCAL)
ffffffff8158c8c0-ffffffff8158c8e8: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816331c0)
Location: fs/fuse/dax.c:1372
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff816331c0-ffffffff81633207: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166b4b0)
Location: fs/fuse/dax.c:1372
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff8166b4b0-ffffffff8166b4f7: fuse_dax_check_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn *fc, unsigned int map_alignment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a5830)
Location: fs/fuse/dax.c:1371
Inline: False
Direct callers:
  - fs/fuse/inode.c:process_init_reply
```
**Symbols:**

```
ffffffff816a5830-ffffffff816a5877: fuse_dax_check_alignment (STB_GLOBAL)
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

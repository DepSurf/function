# Function: <code>kernfs_find_and_get_node_by_ino</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff290)
Location: fs/kernfs/dir.c:695
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff812ff290-ffffffff812ff2da: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cf50)
Location: fs/kernfs/dir.c:712
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8132cf50-ffffffff8132cf99: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813442f0)
Location: fs/kernfs/dir.c:712
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff813442f0-ffffffff81344339: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c510)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8136c510-ffffffff8136c560: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813846c0)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff813846c0-ffffffff81384710: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453478)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffff800010453478-ffff800010453528: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616034)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
c0616034-c06160b4: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c7e0)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
c00000000056c7e0-c00000000056c880: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5ae8)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffe0002e5ae8-ffffffe0002e5b7a: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137cca0)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8137cca0-ffffffff8137ccf0: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d770)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8136d770-ffffffff8136d7c0: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a770)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8137a770-ffffffff8137a7c0: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_node_by_ino(struct kernfs_root *root, unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e260)
Location: fs/kernfs/dir.c:714
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
```
**Symbols:**

```
ffffffff8138e260-ffffffff8138e2ca: kernfs_find_and_get_node_by_ino (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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

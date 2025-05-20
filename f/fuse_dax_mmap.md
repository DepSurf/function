# Function: <code>fuse_dax_mmap</code>

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
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149e020)
Location: fs/fuse/dax.c:863
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff8149e020-ffffffff8149e059: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3ff0)
Location: fs/fuse/dax.c:863
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff814a3ff0-ffffffff814a4029: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fc090)
Location: fs/fuse/dax.c:862
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff814fc090-ffffffff814fc0c9: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158c610)
Location: fs/fuse/dax.c:859
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff8158c610-ffffffff8158c651: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81632ec0)
Location: fs/fuse/dax.c:859
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff81632ec0-ffffffff81632efe: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166b180)
Location: fs/fuse/dax.c:859
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff8166b180-ffffffff8166b1e9: fuse_dax_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_dax_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a54c0)
Location: fs/fuse/dax.c:857
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_mmap
```
**Symbols:**

```
ffffffff816a54c0-ffffffff816a5529: fuse_dax_mmap (STB_GLOBAL)
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

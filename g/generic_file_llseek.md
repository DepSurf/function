# Function: <code>generic_file_llseek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bdd0)
Location: fs/read_write.c:143
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_dir_fop_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
```
**Symbols:**

```
ffffffff8120bdd0-ffffffff8120bdf6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231bf0)
Location: fs/read_write.c:145
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81231bf0-ffffffff81231c16: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812441a0)
Location: fs/read_write.c:145
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812441a0-ffffffff812441c6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f7c0)
Location: fs/read_write.c:143
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8124f7c0-ffffffff8124f7e6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81271700)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81271700-ffffffff81271726: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297430)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81297430-ffffffff81297456: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac0e0)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812ac0e0-ffffffff812ac106: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c8920)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812c8920-ffffffff812c8946: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da330)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812da330-ffffffff812da356: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813105c0)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff813105c0-ffffffff813105e6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131c870)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8131c870-ffffffff8131c896: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813229e0)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff813229e0-ffffffff81322a06: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8136fed0)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff8136fed0-ffffffff8136fef6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ee880)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff813ee880-ffffffff813ee8b5: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477110)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff81477110-ffffffff81477145: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aba70)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff814aba70-ffffffff814abaa5: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dcf10)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff814dcf10-ffffffff814dcf45: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037fa80)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffff80001037fa80-ffff80001037fad8: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056a4cc)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
```
**Symbols:**

```
c056a4cc-c056a564: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475740)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
c000000000475740-c000000000475768: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002552d0)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffe0002552d0-ffffffe000255314: generic_file_llseek (STB_GLOBAL)
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
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2910)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812d2910-ffffffff812d2936: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3590)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812c3590-ffffffff812c35b6: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d0720)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812d0720-ffffffff812d0746: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t generic_file_llseek(struct file *file, loff_t offset, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1550)
Location: fs/read_write.c:144
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_lseek
```
**Symbols:**

```
ffffffff812e1550-ffffffff812e1576: generic_file_llseek (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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

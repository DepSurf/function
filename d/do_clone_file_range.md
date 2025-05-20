# Function: <code>do_clone_file_range</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8125a68e)
Location: include/linux/fs.h:1750
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81267061)
Location: include/linux/fs.h:2687
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812898ed)
Location: include/linux/fs.h:2748
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812afc8c)
Location: include/linux/fs.h:2770
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812acc40)
Location: fs/read_write.c:1974
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812acc40-ffffffff812ace97: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c96b0)
Location: fs/read_write.c:2055
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812c96b0-ffffffff812c987b: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812db0c0)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812db0c0-ffffffff812db28b: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81311d40)
Location: fs/read_write.c:2137
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81311d40-ffffffff81311f07: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81366560)
Location: fs/remap_range.c:375
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81366560-ffffffff81366746: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8136cdf0)
Location: fs/remap_range.c:375
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff8136cdf0-ffffffff8136cffe: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff813bbab0)
Location: fs/remap_range.c:363
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff813bbab0-ffffffff813bbcdb: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81442350)
Location: fs/remap_range.c:358
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81442350-ffffffff8144258a: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d1030)
Location: fs/remap_range.c:367
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff814d1030-ffffffff814d126a: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81507290)
Location: fs/remap_range.c:370
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81507290-ffffffff81507558: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010380b58)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffff800010380b58-ffff800010380d24: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056af04)
Location: fs/read_write.c:2053
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
c056af04-c056b140: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000476870)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
c000000000476870-c000000000476ad4: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025622c)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffe00025622c-ffffffe000256398: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d36a0)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812d36a0-ffffffff812d386b: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4320)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812c4320-ffffffff812c44eb: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d14b0)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812d14b0-ffffffff812d167b: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t do_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e22e0)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812e22e0-ffffffff812e24ab: do_clone_file_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

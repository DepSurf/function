# Function: <code>vfs_clone_file_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231d40)
Location: fs/read_write.c:1648
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81231d40-ffffffff81231f82: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245150)
Location: fs/read_write.c:1801
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81245150-ffffffff81245360: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812505b0)
Location: fs/read_write.c:1817
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812505b0-ffffffff812507c3: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272470)
Location: fs/read_write.c:1820
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81272470-ffffffff81272689: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812984a0)
Location: fs/read_write.c:1847
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812984a0-ffffffff812986c3: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812acea0)
Location: fs/read_write.c:2024
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812acea0-ffffffff812acf46: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c9880)
Location: fs/read_write.c:2097
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812c9880-ffffffff812c9925: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812db290)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812db290-ffffffff812db335: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81311f10)
Location: fs/read_write.c:2179
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81311f10-ffffffff81311fb5: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81366750)
Location: fs/remap_range.c:417
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81366750-ffffffff81366859: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8136d000)
Location: fs/remap_range.c:417
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff8136d000-ffffffff8136d109: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff813bbce0)
Location: fs/remap_range.c:405
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff813bbce0-ffffffff813bbde9: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81442590)
Location: fs/remap_range.c:395
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81442590-ffffffff814426d2: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d1280)
Location: fs/remap_range.c:404
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff814d1280-ffffffff814d13c2: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81507570)
Location: fs/remap_range.c:407
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff81507570-ffffffff815076b8: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153c630)
Location: fs/remap_range.c:376
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff8153c630-ffffffff8153c97e: vfs_clone_file_range (STB_GLOBAL)
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
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010380d28)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffff800010380d28-ffff800010380df4: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056b140)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
c056b140-c056b204: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000476ae0)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
c000000000476ae0-c000000000476c0c: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256398)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffe000256398-ffffffe00025642c: vfs_clone_file_range (STB_GLOBAL)
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
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3870)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812d3870-ffffffff812d3915: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c44f0)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812c44f0-ffffffff812c4595: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d1680)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812d1680-ffffffff812d1725: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e24b0)
Location: fs/read_write.c:2095
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_clone
```
**Symbols:**

```
ffffffff812e24b0-ffffffff812e2555: vfs_clone_file_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int remap_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>u64 len</code> ➡️ <code>loff_t len</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>loff_t</code>
</li>
</ul>
</details>
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

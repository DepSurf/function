# Function: <code>vfs_copy_file_range</code>

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
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233dc0)
Location: fs/read_write.c:1505
Inline: False
Direct callers:
  - fs/read_write.c:SyS_copy_file_range
```
**Symbols:**

```
ffffffff81233dc0-ffffffff8123402c: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81246950)
Location: fs/read_write.c:1534
Inline: False
Direct callers:
  - fs/read_write.c:SyS_copy_file_range
```
**Symbols:**

```
ffffffff81246950-ffffffff81246bde: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251f70)
Location: fs/read_write.c:1545
Inline: False
Direct callers:
  - fs/read_write.c:SyS_copy_file_range
```
**Symbols:**

```
ffffffff81251f70-ffffffff81252278: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812738e0)
Location: fs/read_write.c:1548
Inline: False
Direct callers:
  - fs/read_write.c:SyS_copy_file_range
```
**Symbols:**

```
ffffffff812738e0-ffffffff81273bee: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129a220)
Location: fs/read_write.c:1575
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff8129a220-ffffffff8129a52f: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812af0b0)
Location: fs/read_write.c:1571
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812af0b0-ffffffff812af405: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cbd60)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812cbd60-ffffffff812cc06a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dd780)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812dd780-ffffffff812dda8a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81314760)
Location: fs/read_write.c:1735
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff81314760-ffffffff81314a6a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81320870)
Location: fs/read_write.c:1473
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff81320870-ffffffff81320be0: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81326890)
Location: fs/read_write.c:1478
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff81326890-ffffffff81326cda: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373e30)
Location: fs/read_write.c:1469
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff81373e30-ffffffff8137429a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2d10)
Location: fs/read_write.c:1479
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff813f2d10-ffffffff813f3220: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b9c0)
Location: fs/read_write.c:1476
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff8147b9c0-ffffffff8147bf1b: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814b0540)
Location: fs/read_write.c:1475
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff814b0540-ffffffff814b0b12: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e1d00)
Location: fs/read_write.c:1483
Inline: False
Direct callers:
  - fs/read_write.c:__do_sys_copy_file_range
```
**Symbols:**

```
ffffffff814e1d00-ffffffff814e22d7: vfs_copy_file_range (STB_GLOBAL)
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
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010383688)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_sys_copy_file_range
```
**Symbols:**

```
ffff800010383688-ffff8000103839a0: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056cb04)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_copy_file_range
```
**Symbols:**

```
c056cb04-c056cee4: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004799e0)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_copy_file_range
```
**Symbols:**

```
c0000000004799e0-c000000000479e1c: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257004)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_copy_file_range
```
**Symbols:**

```
ffffffe000257004-ffffffe00025726a: vfs_copy_file_range (STB_GLOBAL)
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
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d5d60)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812d5d60-ffffffff812d606a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c69e0)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812c69e0-ffffffff812c6cea: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3b70)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812d3b70-ffffffff812d3e7a: vfs_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e49d0)
Location: fs/read_write.c:1651
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
```
**Symbols:**

```
ffffffff812e49d0-ffffffff812e4cda: vfs_copy_file_range (STB_GLOBAL)
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

# Function: <code>vfs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c820)
Location: fs/read_write.c:547
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_pwrite64
  - fs/splice.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8120c820-ffffffff8120c9b9: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81232c40)
Location: fs/read_write.c:568
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_write
  - fs/splice.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81232c40-ffffffff81232dd4: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812457c0)
Location: fs/read_write.c:568
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_write
  - fs/splice.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812457c0-ffffffff81245954: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250c30)
Location: fs/read_write.c:526
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_write
  - fs/splice.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81250c30-ffffffff81250dc8: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273ee0)
Location: fs/read_write.c:553
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81273ee0-ffffffff81274078: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129ac40)
Location: fs/read_write.c:558
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8129ac40-ffffffff8129ade5: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812afb40)
Location: fs/read_write.c:558
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812afb40-ffffffff812afcea: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca1c0)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812ca1c0-ffffffff812ca359: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbbe0)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812dbbe0-ffffffff812dbd79: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312590)
Location: fs/read_write.c:591
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81312590-ffffffff81312781: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131dbc0)
Location: fs/read_write.c:586
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff8131dbc0-ffffffff8131de30: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81325f60)
Location: fs/read_write.c:585
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff81325f60-ffffffff813261ac: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81371210)
Location: fs/read_write.c:575
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff81371210-ffffffff8137146c: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2200)
Location: fs/read_write.c:571
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff813f2200-ffffffff813f248e: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147ac20)
Location: fs/read_write.c:564
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff8147ac20-ffffffff8147b024: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814af780)
Location: fs/read_write.c:564
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff814af780-ffffffff814afbb5: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0f00)
Location: fs/read_write.c:570
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
```
**Symbols:**

```
ffffffff814e0f00-ffffffff814e1376: vfs_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381588)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffff800010381588-ffff80001038174c: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056bdac)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
c056bdac-c056bf74: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477900)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
c000000000477900-c000000000477b98: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002565ee)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffe0002565ee-ffffffe000256750: vfs_write (STB_GLOBAL)
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
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d41c0)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812d41c0-ffffffff812d4359: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4e40)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812c4e40-ffffffff812c4fd9: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d1fd0)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812d1fd0-ffffffff812d2169: vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_write(struct file *file, const char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2e30)
Location: fs/read_write.c:567
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_write
  - fs/read_write.c:kernel_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff812e2e30-ffffffff812e2fc9: vfs_write (STB_GLOBAL)
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

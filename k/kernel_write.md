# Function: <code>kernel_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123da60)
Location: fs/splice.c:588
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_dn_node_address
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff8123da60-ffffffff8123daa8: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81265b30)
Location: fs/splice.c:589
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81265b30-ffffffff81265b78: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279180)
Location: fs/splice.c:370
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81279180-ffffffff812791c8: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const char *buf, size_t count, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812866f0)
Location: fs/splice.c:367
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812866f0-ffffffff81286738: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81274080)
Location: fs/read_write.c:537
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81274080-ffffffff812740c2: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129adf0)
Location: fs/read_write.c:542
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff8129adf0-ffffffff8129ae32: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812afcf0)
Location: fs/read_write.c:542
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812afcf0-ffffffff812afd32: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca360)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812ca360-ffffffff812ca3a2: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbd80)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812dbd80-ffffffff812dbdc2: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813124d0)
Location: fs/read_write.c:575
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff813124d0-ffffffff81312584: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131dac0)
Location: fs/read_write.c:570
Inline: True
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff8131dac0-ffffffff8131dbb7: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81323830)
Location: fs/read_write.c:569
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff81323830-ffffffff81323988: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81370d30)
Location: fs/read_write.c:559
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff81370d30-ffffffff81370e88: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0fd0)
Location: fs/read_write.c:555
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff813f0fd0-ffffffff813f1160: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147aa50)
Location: fs/read_write.c:548
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff8147aa50-ffffffff8147ac08: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814af5b0)
Location: fs/read_write.c:548
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff814af5b0-ffffffff814af76e: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0d30)
Location: fs/read_write.c:554
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
**Symbols:**

```
ffffffff814e0d30-ffffffff814e0eee: kernel_write (STB_GLOBAL)
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
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381750)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffff800010381750-ffff800010381828: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056bf74)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
c056bf74-c056bfc8: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477ba0)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
c000000000477ba0-c000000000477c2c: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256750)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffe000256750-ffffffe0002567a4: kernel_write (STB_GLOBAL)
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
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4360)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812d4360-ffffffff812d43a2: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4fe0)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812c4fe0-ffffffff812c5022: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2170)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812d2170-ffffffff812d21b2: kernel_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t kernel_write(struct file *file, const void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2fd0)
Location: fs/read_write.c:551
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff812e2fd0-ffffffff812e3012: kernel_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char *buf</code> ➡️ <code>const void *buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>loff_t pos</code> ➡️ <code>loff_t *pos</code>
</li>
</ul>
</details>
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

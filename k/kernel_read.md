# Function: <code>kernel_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212660)
Location: fs/exec.c:829
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/kexec_file.c:copy_file_from_fd
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff81212660-ffffffff812126d4: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81239140)
Location: fs/exec.c:869
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff81239140-ffffffff812391b4: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124bdf0)
Location: fs/exec.c:874
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff8124bdf0-ffffffff8124be64: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81257f10)
Location: fs/exec.c:900
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff81257f10-ffffffff81257f84: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273d60)
Location: fs/read_write.c:418
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/exec.c:prepare_binprm
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff81273d60-ffffffff81273da2: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129aab0)
Location: fs/read_write.c:423
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff8129aab0-ffffffff8129aaf2: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812af9b0)
Location: fs/read_write.c:423
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812af9b0-ffffffff812af9f2: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc630)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812cc630-ffffffff812cc672: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de050)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812de050-ffffffff812de092: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81314e30)
Location: fs/read_write.c:450
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff81314e30-ffffffff81314e7f: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813201b0)
Location: fs/read_write.c:465
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff813201b0-ffffffff813201ff: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81325bb0)
Location: fs/read_write.c:465
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff81325bb0-ffffffff81325c41: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373830)
Location: fs/read_write.c:454
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff81373830-ffffffff813738c1: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f1e10)
Location: fs/read_write.c:451
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff813f1e10-ffffffff813f1eb7: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a170)
Location: fs/read_write.c:439
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff8147a170-ffffffff8147a217: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aec70)
Location: fs/read_write.c:439
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff814aec70-ffffffff814aed17: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e03d0)
Location: fs/read_write.c:445
Inline: False
Direct callers:
  - fs/exec.c:search_binary_handler
  - fs/kernel_read_file.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
```
**Symbols:**

```
ffffffff814e03d0-ffffffff814e0429: kernel_read (STB_GLOBAL)
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
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384240)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffff800010384240-ffff800010384318: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d0a8)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:elf_fdpic_fetch_phdrs
  - fs/binfmt_flat.c:load_flat_shared_library
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
c056d0a8-c056d0fc: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a300)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
c00000000047a300-c00000000047a38c: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257402)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/binfmt_flat.c:load_flat_shared_library
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffe000257402-ffffffe000257456: kernel_read (STB_GLOBAL)
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
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6630)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812d6630-ffffffff812d6672: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c72b0)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812c72b0-ffffffff812c72f2: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4440)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812d4440-ffffffff812d4482: kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e52a0)
Location: fs/read_write.c:432
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - fs/exec.c:kernel_read_file
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_phdrs
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_phdrs
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff812e52a0-ffffffff812e52e2: kernel_read (STB_GLOBAL)
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
<b>Param added. </b>
<code>void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t *pos</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>char *addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, offset, addr, count</code> ➡️ <code>file, buf, count, pos</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
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

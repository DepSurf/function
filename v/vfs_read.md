# Function: <code>vfs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c6f0)
Location: fs/read_write.c:440
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_pread64
  - fs/exec.c:kernel_read
  - fs/exec.c:read_code
  - security/keys/big_key.c:big_key_read
```
**Symbols:**

```
ffffffff8120c6f0-ffffffff8120c816: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81232b10)
Location: fs/read_write.c:460
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff81232b10-ffffffff81232c3f: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245690)
Location: fs/read_write.c:460
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff81245690-ffffffff812457bf: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250b00)
Location: fs/read_write.c:418
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff81250b00-ffffffff81250c2c: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273c30)
Location: fs/read_write.c:432
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff81273c30-ffffffff81273d5c: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129a970)
Location: fs/read_write.c:437
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff8129a970-ffffffff8129aaab: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812af850)
Location: fs/read_write.c:437
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812af850-ffffffff812af9a2: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc4d0)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812cc4d0-ffffffff812cc624: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ddef0)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812ddef0-ffffffff812de044: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813121c0)
Location: fs/read_write.c:461
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff813121c0-ffffffff8131234d: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131d780)
Location: fs/read_write.c:476
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff8131d780-ffffffff8131d932: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81325c50)
Location: fs/read_write.c:476
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff81325c50-ffffffff81325dd6: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81370ef0)
Location: fs/read_write.c:465
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff81370ef0-ffffffff81371086: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f1ec0)
Location: fs/read_write.c:462
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff813f1ec0-ffffffff813f2063: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a230)
Location: fs/read_write.c:450
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff8147a230-ffffffff8147a551: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aed30)
Location: fs/read_write.c:450
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff814aed30-ffffffff814af083: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0440)
Location: fs/read_write.c:456
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
```
**Symbols:**

```
ffffffff814e0440-ffffffff814e07c9: vfs_read (STB_GLOBAL)
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
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103840a0)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffff8000103840a0-ffff80001038423c: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056cf2c)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
c056cf2c-c056d0a8: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a100)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
c00000000047a100-c00000000047a2f8: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002572d4)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffe0002572d4-ffffffe000257402: vfs_read (STB_GLOBAL)
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
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d64d0)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812d64d0-ffffffff812d6624: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7150)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:bin_string
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812c7150-ffffffff812c72a4: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d42e0)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812d42e0-ffffffff812d4434: vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5140)
Location: fs/read_write.c:446
Inline: True
Direct callers:
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_read
  - fs/read_write.c:kernel_read
  - fs/exec.c:read_code
```
**Symbols:**

```
ffffffff812e5140-ffffffff812e5294: vfs_read (STB_GLOBAL)
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

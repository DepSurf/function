# Function: <code>shmem_kernel_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811abb60)
Location: mm/shmem.c:3413
Inline: False
Direct callers:
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff811abb60-ffffffff811abb75: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c4550)
Location: mm/shmem.c:4174
Inline: False
Direct callers:
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff811c4550-ffffffff811c4565: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d4640)
Location: mm/shmem.c:4068
Inline: False
Direct callers:
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff811d4640-ffffffff811d4655: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dd2f0)
Location: mm/shmem.c:4233
Inline: False
Direct callers:
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff811dd2f0-ffffffff811dd322: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2db5)
Location: mm/shmem.c:4279
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff811f2d70-ffffffff811f2db0: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213fc5)
Location: mm/shmem.c:3995
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81213f80-ffffffff81213fbf: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81225a25)
Location: mm/shmem.c:3954
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81226f40-ffffffff81226f7f: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81232bfa)
Location: mm/shmem.c:4035
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81236ac0-ffffffff81236aff: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240e1a)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81244d00-ffffffff81244d3f: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271e15)
Location: mm/shmem.c:4120
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812729c0-ffffffff812729e6: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ce65)
Location: mm/shmem.c:4227
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8127d0a0-ffffffff8127d0c6: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81282125)
Location: mm/shmem.c:4171
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81282240-ffffffff81282266: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bf7c5)
Location: mm/shmem.c:4107
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812c02b0-ffffffff812c02d6: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131cce5)
Location: mm/shmem.c:4119
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8131cca0-ffffffff8131ccd5: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813907f5)
Location: mm/shmem.c:4248
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813907a0-ffffffff813907d5: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813c30e5)
Location: mm/shmem.c:4457
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813c3090-ffffffff813c30c5: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813edc05)
Location: mm/shmem.c:4832
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813edbb0-ffffffff813edbe5: shmem_kernel_file_setup (STB_GLOBAL)
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
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d29d0)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffff8000102d7428-ffff8000102d7498: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa450)
Location: mm/shmem.c:4157
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
c04ff12c-c04ff16c: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003903c4)
Location: mm/shmem.c:4157
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
c000000000397630-c00000000039768c: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef64a)
Location: mm/shmem.c:4157
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffe0001f25c6-ffffffe0001f2626: shmem_kernel_file_setup (STB_GLOBAL)
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
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123946a)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff8123d350-ffffffff8123d38f: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c4aa)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff81230350-ffffffff8123038f: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123720a)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff8123b0f0-ffffffff8123b12f: shmem_kernel_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_kernel_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244fba)
Location: mm/shmem.c:4157
Inline: True
Direct callers:
  - kernel/umh.c:fork_usermode_blob
  - ipc/shm.c:newseg
  - security/keys/big_key.c:big_key_preparse
```
**Symbols:**

```
ffffffff8124a800-ffffffff8124a83f: shmem_kernel_file_setup (STB_GLOBAL)
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

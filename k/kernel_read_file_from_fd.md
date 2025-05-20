# Function: <code>kernel_read_file_from_fd</code>

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
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81239720)
Location: fs/exec.c:977
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81239720-ffffffff81239792: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c460)
Location: fs/exec.c:982
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8124c460-ffffffff8124c4d2: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81258570)
Location: fs/exec.c:1008
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81258570-ffffffff812585e2: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a8e0)
Location: fs/exec.c:989
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8127a8e0-ffffffff8127a952: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a1420)
Location: fs/exec.c:993
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812a1420-ffffffff812a14a1: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b66c0)
Location: fs/exec.c:996
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812b66c0-ffffffff812b6741: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d3420)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812d3420-ffffffff812d34a1: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4fb0)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812e4fb0-ffffffff812e5031: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131c060)
Location: fs/exec.c:1048
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8131c060-ffffffff8131c0e1: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81365e20)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81365e20-ffffffff81365ea9: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8136c860)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8136c860-ffffffff8136c8e9: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff813bb530)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff813bb530-ffffffff813bb5bf: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81441650)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81441650-ffffffff81441709: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff814d05f0)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff814d05f0-ffffffff814d06ad: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff815068a0)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff815068a0-ffffffff8150695d: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8153b5c0)
Location: fs/kernel_read_file.c:174
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_prepare_segments
  - kernel/kexec_file.c:kimage_file_prepare_segments
```
**Symbols:**

```
ffffffff8153b5c0-ffffffff8153b67d: kernel_read_file_from_fd (STB_GLOBAL)
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
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038ca88)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff80001038ca88-ffff80001038cb2c: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c05746b8)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_finit_module
```
**Symbols:**

```
c05746b8-c057473c: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000484af0)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c000000000484af0-c000000000484be0: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025e022)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
```
**Symbols:**

```
ffffffe00025e022-ffffffe00025e09e: kernel_read_file_from_fd (STB_GLOBAL)
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
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd590)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812dd590-ffffffff812dd611: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ce210)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812ce210-ffffffff812ce291: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812db3a0)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812db3a0-ffffffff812db421: kernel_read_file_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ec320)
Location: fs/exec.c:997
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff812ec320-ffffffff812ec3a1: kernel_read_file_from_fd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t *size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>fd, buf, size, max_size, id</code> ➡️ <code>fd, offset, buf, buf_size, file_size, id</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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

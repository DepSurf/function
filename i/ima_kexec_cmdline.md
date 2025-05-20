# Function: <code>ima_kexec_cmdline</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149ca60)
Location: security/integrity/ima/ima_main.c:671
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8149ca60-ffffffff8149cadb: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814b6df0)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff814b6df0-ffffffff814b6e19: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff815165f0)
Location: security/integrity/ima/ima_main.c:823
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff815165f0-ffffffff8151661c: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff815337b0)
Location: security/integrity/ima/ima_main.c:911
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff815337b0-ffffffff8153382a: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153bdb0)
Location: security/integrity/ima/ima_main.c:946
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8153bdb0-ffffffff8153be36: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8159aa10)
Location: security/integrity/ima/ima_main.c:978
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8159aa10-ffffffff8159aa9a: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163f7c0)
Location: security/integrity/ima/ima_main.c:998
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8163f7c0-ffffffff8163f870: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f7560)
Location: security/integrity/ima/ima_main.c:1008
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff816f7560-ffffffff816f761b: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff817317e0)
Location: security/integrity/ima/ima_main.c:1027
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff817317e0-ffffffff81731896: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ima_kexec_cmdline(int kernel_fd, const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81772200)
Location: security/integrity/ima/ima_main.c:1041
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_prepare_segments
```
**Symbols:**

```
ffffffff81772200-ffffffff817722b6: ima_kexec_cmdline (STB_GLOBAL)
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
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105af118)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000105af118-ffff8000105af174: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e83c)
Location: security/integrity/ima/ima_main.c:717
Inline: False
```
**Symbols:**

```
c075e83c-c075e888: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072e3b0)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c00000000072e3b0-c00000000072e3e4: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f709c)
Location: security/integrity/ima/ima_main.c:717
Inline: False
```
**Symbols:**

```
ffffffe0003f709c-ffffffe0003f70ec: ima_kexec_cmdline (STB_GLOBAL)
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
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814af3d0)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff814af3d0-ffffffff814af3f9: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149fdf0)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8149fdf0-ffffffff8149fe19: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814ab460)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff814ab460-ffffffff814ab489: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814c3eb0)
Location: security/integrity/ima/ima_main.c:717
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff814c3eb0-ffffffff814c3ed9: ima_kexec_cmdline (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>int kernel_fd</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, size</code> ➡️ <code>kernel_fd, buf, size</code>
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

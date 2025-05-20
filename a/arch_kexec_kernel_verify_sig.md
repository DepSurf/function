# Function: <code>arch_kexec_kernel_verify_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *kernel, long unsigned int kernel_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c060)
Location: arch/x86/kernel/machine_kexec_64.c:388
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105c060-ffffffff8105c0b8: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *kernel, long unsigned int kernel_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c1d0)
Location: arch/x86/kernel/machine_kexec_64.c:389
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105c1d0-ffffffff8105c221: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *kernel, long unsigned int kernel_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f150)
Location: arch/x86/kernel/machine_kexec_64.c:390
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105f150-ffffffff8105f1a1: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *kernel, long unsigned int kernel_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e830)
Location: arch/x86/kernel/machine_kexec_64.c:408
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105e830-ffffffff8105e881: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *kernel, long unsigned int kernel_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81062570)
Location: arch/x86/kernel/machine_kexec_64.c:410
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81062570-ffffffff810625c4: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81138c90)
Location: kernel/kexec_file.c:106
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81138c90-ffffffff81138ce4: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811445c0)
Location: kernel/kexec_file.c:105
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811445c0-ffffffff81144614: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8114f950)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8114f950-ffffffff8114f9a1: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115b630)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8115b630-ffffffff8115b681: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116c620)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8116c620-ffffffff8116c671: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81168c60)
Location: kernel/kexec_file.c:104
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81168c60-ffffffff81168cb1: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169a10)
Location: kernel/kexec_file.c:104
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81169a10-ffffffff81169a61: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118f5b0)
Location: kernel/kexec_file.c:104
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8118f5b0-ffffffff8118f5fe: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cac58)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000101cac58-ffff8000101cacd0: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81153c50)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81153c50-ffffffff81153ca1: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81146f70)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81146f70-ffffffff81146fc1: arch_kexec_kernel_verify_sig (STB_WEAK)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_kexec_kernel_verify_sig(struct kimage *image, void *buf, long unsigned int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115e920)
Location: kernel/kexec_file.c:103
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8115e920-ffffffff8115e971: arch_kexec_kernel_verify_sig (STB_WEAK)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int buf_len</code>
</li>
<li>
<b>Param removed. </b>
<code>void *kernel</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int kernel_len</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

# Function: <code>kimage_file_alloc_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8110f198)
Location: kernel/kexec_file.c:253
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81116817)
Location: kernel/kexec_file.c:200
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111df57)
Location: kernel/kexec_file.c:204
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111fb39)
Location: kernel/kexec_file.c:191
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8112b2d9)
Location: kernel/kexec_file.c:191
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:264
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81138da0-ffffffff81139014: kimage_file_alloc_init (STB_LOCAL)
ffffffff8113a2c4-ffffffff8113a2fe: kimage_file_alloc_init.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:263
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811446d0-ffffffff81144944: kimage_file_alloc_init (STB_LOCAL)
ffffffff81145b94-ffffffff81145bce: kimage_file_alloc_init.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:309
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8114fa60-ffffffff8114fd4c: kimage_file_alloc_init (STB_LOCAL)
ffffffff81150f26-ffffffff81150f74: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:314
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8115b740-ffffffff8115b9d3: kimage_file_alloc_init (STB_LOCAL)
ffffffff8115cbb6-ffffffff8115cc04: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:292
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8116c810-ffffffff8116caba: kimage_file_alloc_init (STB_LOCAL)
ffffffff8116d8f6-ffffffff8116d930: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:298
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81168e50-ffffffff811690cf: kimage_file_alloc_init (STB_LOCAL)
ffffffff81be462c-ffffffff81be4666: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:298
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81169b20-ffffffff81169d9f: kimage_file_alloc_init (STB_LOCAL)
ffffffff81bd644d-ffffffff81bd6487: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:298
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8118f6b0-ffffffff8118f92f: kimage_file_alloc_init (STB_LOCAL)
ffffffff81cb2d3a-ffffffff81cb2d74: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:265
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811bed70-ffffffff811bf098: kimage_file_alloc_init (STB_LOCAL)
ffffffff81e63b10-ffffffff81e63b6a: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:269
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81200f50-ffffffff81201302: kimage_file_alloc_init (STB_LOCAL)
ffffffff8205c096-ffffffff8205c0ab: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:269
Inline: False
Direct callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff812162d0-ffffffff812166dd: kimage_file_alloc_init (STB_LOCAL)
ffffffff820da88d-ffffffff820da8a2: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122f05b)
Location: kernel/kexec_file.c:273
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cadd8)
Location: kernel/kexec_file.c:314
Inline: True
Inline callers:
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c0000000002348c4)
Location: kernel/kexec_file.c:314
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:314
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81153d60-ffffffff81153ff3: kimage_file_alloc_init (STB_LOCAL)
ffffffff811551d6-ffffffff81155224: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:314
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81147080-ffffffff81147313: kimage_file_alloc_init (STB_LOCAL)
ffffffff811484f6-ffffffff81148544: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:314
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81151bb0-ffffffff81151dd7: kimage_file_alloc_init (STB_LOCAL)
ffffffff81152fb6-ffffffff81152ff0: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kimage_file_alloc_init(struct kimage **rimage, int kernel_fd, int initrd_fd, const char *cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:314
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8115ea30-ffffffff8115ecc3: kimage_file_alloc_init (STB_LOCAL)
ffffffff8115fea6-ffffffff8115fef4: kimage_file_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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

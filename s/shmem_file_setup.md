# Function: <code>shmem_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8010)
Location: mm/shmem.c:3424
Inline: True
Inline callers:
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811a8010-ffffffff811a8022: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c441f)
Location: mm/shmem.c:4185
Inline: True
Inline callers:
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811bf070-ffffffff811bf082: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d451f)
Location: mm/shmem.c:4079
Inline: True
Inline callers:
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811cecd0-ffffffff811cece2: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dd19f)
Location: mm/shmem.c:4244
Inline: True
Inline callers:
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811d8480-ffffffff811d84af: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2c0c)
Location: mm/shmem.c:4290
Inline: True
Inline callers:
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811ed9e0-ffffffff811eda1d: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812106b0)
Location: mm/shmem.c:4006
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff812106b0-ffffffff812106ec: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812259b0)
Location: mm/shmem.c:3965
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff812259b0-ffffffff812259ec: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81232b70)
Location: mm/shmem.c:4046
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff81232b70-ffffffff81232bac: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240d90)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff81240d90-ffffffff81240dcc: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271dc0)
Location: mm/shmem.c:4131
Inline: False
Direct callers:
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff81271dc0-ffffffff81271de3: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278d00)
Location: mm/shmem.c:4238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff81278d00-ffffffff81278d23: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127dcb0)
Location: mm/shmem.c:4182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff8127dcb0-ffffffff8127dcd3: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bbbc0)
Location: mm/shmem.c:4118
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff812bbbc0-ffffffff812bbbe3: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813168e0)
Location: mm/shmem.c:4130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff813168e0-ffffffff81316912: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b280)
Location: mm/shmem.c:4259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff8138b280-ffffffff8138b2b2: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bc990)
Location: mm/shmem.c:4468
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
```
**Symbols:**

```
ffffffff813bc990-ffffffff813bc9c2: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8c80)
Location: mm/shmem.c:4843
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - mm/memfd.c:__do_sys_memfd_create
  - drivers/gpu/drm/drm_gem.c:drm_gem_object_init
```
**Symbols:**

```
ffffffff813e8c80-ffffffff813e8cb2: shmem_file_setup (STB_GLOBAL)
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
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d28b8)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__arm64_sys_memfd_create
```
**Symbols:**

```
ffff8000102d28b8-ffff8000102d2928: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa3c8)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__se_sys_memfd_create
```
**Symbols:**

```
c04fa3c8-c04fa408: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003902f0)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__se_sys_memfd_create
```
**Symbols:**

```
c0000000003902f0-c00000000039034c: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef56c)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__se_sys_memfd_create
```
**Symbols:**

```
ffffffe0001ef56c-ffffffe0001ef5ca: shmem_file_setup (STB_GLOBAL)
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
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812393e0)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff812393e0-ffffffff8123941c: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c420)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff8122c420-ffffffff8122c45c: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237180)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff81237180-ffffffff812371bc: shmem_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *shmem_file_setup(const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244f30)
Location: mm/shmem.c:4168
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
```
**Symbols:**

```
ffffffff81244f30-ffffffff81244f6c: shmem_file_setup (STB_GLOBAL)
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

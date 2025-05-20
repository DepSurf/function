# Function: <code>kimage_alloc_control_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110cd40)
Location: kernel/kexec_core.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8110cd40-ffffffff8110cf71: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81114670)
Location: kernel/kexec_core.c:471
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81114670-ffffffff811148a1: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111bd90)
Location: kernel/kexec_core.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111bd90-ffffffff8111bfbf: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111dae0)
Location: kernel/kexec_core.c:468
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111dae0-ffffffff8111dd13: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811292d0)
Location: kernel/kexec_core.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff811292d0-ffffffff81129503: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81137220)
Location: kernel/kexec_core.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81137220-ffffffff8113745d: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811429a0)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811429a0-ffffffff81142bf1: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114dd00)
Location: kernel/kexec_core.c:481
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8114dd00-ffffffff8114df26: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81159a10)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81159a10-ffffffff81159c36: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116ae47)
Location: kernel/kexec_core.c:483
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8116ade0-ffffffff8116ae00: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167587)
Location: kernel/kexec_core.c:482
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81167520-ffffffff81167540: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81168317)
Location: kernel/kexec_core.c:483
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811682b0-ffffffff811682d0: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118e057)
Location: kernel/kexec_core.c:484
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8118dff0-ffffffff8118e010: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bd5a7)
Location: kernel/kexec_core.c:484
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811bd520-ffffffff811bd550: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811ff59b)
Location: kernel/kexec_core.c:484
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811ff500-ffffffff811ff530: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8121499b)
Location: kernel/kexec_core.c:485
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81214900-ffffffff81214930: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122c93b)
Location: kernel/kexec_core.c:473
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8122c8a0-ffffffff8122c8d0: kimage_alloc_control_pages (STB_GLOBAL)
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
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c90a0)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000101c90a0-ffff8000101c9298: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c040ff48)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
c040ff48-c04101ec: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c000000000231850)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c000000000231850-c000000000231ac4: kimage_alloc_control_pages (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81152030)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81152030-ffffffff81152256: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81145310)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81145310-ffffffff81145536: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114fee0)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8114fee0-ffffffff81150106: kimage_alloc_control_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *kimage_alloc_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115cd40)
Location: kernel/kexec_core.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8115cd40-ffffffff8115cf5e: kimage_alloc_control_pages (STB_GLOBAL)
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

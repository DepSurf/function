# Function: <code>kimage_alloc_normal_control_pages</code>

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
In kernel/kexec_core.c (ffffffff8110ce4f)
Location: kernel/kexec_core.c:324
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
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
In kernel/kexec_core.c (ffffffff8111477f)
Location: kernel/kexec_core.c:344
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
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
In kernel/kexec_core.c (ffffffff8111bebe)
Location: kernel/kexec_core.c:344
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
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
In kernel/kexec_core.c (ffffffff8111dbef)
Location: kernel/kexec_core.c:339
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
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
In kernel/kexec_core.c (ffffffff811293df)
Location: kernel/kexec_core.c:349
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81137267)
Location: kernel/kexec_core.c:349
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811429e7)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114dd47)
Location: kernel/kexec_core.c:348
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81159a57)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116a910)
Location: kernel/kexec_core.c:350
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff8116a910-ffffffff8116aaad: kimage_alloc_normal_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167050)
Location: kernel/kexec_core.c:349
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81167050-ffffffff811671ed: kimage_alloc_normal_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167de0)
Location: kernel/kexec_core.c:350
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81167de0-ffffffff81167f7d: kimage_alloc_normal_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:351
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff8118d700-ffffffff8118d943: kimage_alloc_normal_control_pages (STB_LOCAL)
ffffffff81cb2c44-ffffffff81cb2c5c: kimage_alloc_normal_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:351
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff811bcbe0-ffffffff811bce33: kimage_alloc_normal_control_pages (STB_LOCAL)
ffffffff81e63a6f-ffffffff81e63a87: kimage_alloc_normal_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:351
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff811feb80-ffffffff811fedd3: kimage_alloc_normal_control_pages (STB_LOCAL)
ffffffff8205c027-ffffffff8205c03f: kimage_alloc_normal_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:352
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81213f80-ffffffff812141d3: kimage_alloc_normal_control_pages (STB_LOCAL)
ffffffff820da81e-ffffffff820da836: kimage_alloc_normal_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_normal_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff8122bed0-ffffffff8122c12b: kimage_alloc_normal_control_pages (STB_LOCAL)
ffffffff821b63c9-ffffffff821b63e1: kimage_alloc_normal_control_pages.cold (STB_LOCAL)
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
In kernel/kexec_core.c (ffff8000101c90ec)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c040ff94)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0000000002318bc)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81152077)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81145357)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114ff27)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115cd87)
Location: kernel/kexec_core.c:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

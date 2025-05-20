# Function: <code>kimage_alloc_crash_control_pages</code>

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
In kernel/kexec_core.c (ffffffff8110cd77)
Location: kernel/kexec_core.c:390
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
In kernel/kexec_core.c (ffffffff811146a7)
Location: kernel/kexec_core.c:410
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
In kernel/kexec_core.c (ffffffff8111bdc7)
Location: kernel/kexec_core.c:410
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
In kernel/kexec_core.c (ffffffff8111db1e)
Location: kernel/kexec_core.c:405
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
In kernel/kexec_core.c (ffffffff8112930e)
Location: kernel/kexec_core.c:415
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
In kernel/kexec_core.c (ffffffff81137378)
Location: kernel/kexec_core.c:415
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
In kernel/kexec_core.c (ffffffff81142af1)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (ffffffff8114de39)
Location: kernel/kexec_core.c:414
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
In kernel/kexec_core.c (ffffffff81159b49)
Location: kernel/kexec_core.c:416
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
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81169d10)
Location: kernel/kexec_core.c:416
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81169d10-ffffffff81169e55: kimage_alloc_crash_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81166450)
Location: kernel/kexec_core.c:415
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81166450-ffffffff81166595: kimage_alloc_crash_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811671f0)
Location: kernel/kexec_core.c:416
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff811671f0-ffffffff81167334: kimage_alloc_crash_control_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:417
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff8118c9d0-ffffffff8118cba3: kimage_alloc_crash_control_pages (STB_LOCAL)
ffffffff81cb2bf5-ffffffff81cb2c2e: kimage_alloc_crash_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:417
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff811bbf30-ffffffff811bc0ef: kimage_alloc_crash_control_pages (STB_LOCAL)
ffffffff81e63a27-ffffffff81e63a59: kimage_alloc_crash_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:417
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff811fde40-ffffffff811fe000: kimage_alloc_crash_control_pages (STB_LOCAL)
ffffffff8205bfdf-ffffffff8205c011: kimage_alloc_crash_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:418
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff81212fd0-ffffffff81213190: kimage_alloc_crash_control_pages (STB_LOCAL)
ffffffff820da7d6-ffffffff820da808: kimage_alloc_crash_control_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *kimage_alloc_crash_control_pages(struct kimage *image, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:406
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
**Symbols:**

```
ffffffff8122aef0-ffffffff8122b0b7: kimage_alloc_crash_control_pages (STB_LOCAL)
ffffffff821b6381-ffffffff821b63b3: kimage_alloc_crash_control_pages.cold (STB_LOCAL)
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
In kernel/kexec_core.c (ffff8000101c91e0)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (c04100ec)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (c0000000002319e0)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (ffffffff81152169)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (ffffffff81145449)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (ffffffff81150019)
Location: kernel/kexec_core.c:416
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
In kernel/kexec_core.c (ffffffff8115ce79)
Location: kernel/kexec_core.c:416
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

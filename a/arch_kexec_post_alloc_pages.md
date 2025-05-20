# Function: <code>arch_kexec_post_alloc_pages</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810628e0)
Location: arch/x86/kernel/machine_kexec_64.c:609
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810628e0-ffffffff810628f0: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065840)
Location: arch/x86/kernel/machine_kexec_64.c:559
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81065840-ffffffff81065850: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b510)
Location: arch/x86/kernel/machine_kexec_64.c:559
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff8106b510-ffffffff8106b520: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f000)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff8106f000-ffffffff8106f033: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810705b0)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810705b0-ffffffff810705e3: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077900)
Location: arch/x86/kernel/machine_kexec_64.c:599
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81077900-ffffffff81077933: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f30)
Location: arch/x86/kernel/machine_kexec_64.c:599
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81077f30-ffffffff81077f63: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810789c0)
Location: arch/x86/kernel/machine_kexec_64.c:599
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810789c0-ffffffff810789f3: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81086210)
Location: arch/x86/kernel/machine_kexec_64.c:570
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81086210-ffffffff81086243: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81096620)
Location: arch/x86/kernel/machine_kexec_64.c:579
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81096620-ffffffff8109665e: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ac360)
Location: arch/x86/kernel/machine_kexec_64.c:579
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810ac360-ffffffff810ac39e: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afe90)
Location: arch/x86/kernel/machine_kexec_64.c:568
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810afe90-ffffffff810afece: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6a20)
Location: arch/x86/kernel/machine_kexec_64.c:565
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff810b6a20-ffffffff810b6a5e: arch_kexec_post_alloc_pages (STB_GLOBAL)
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
In kernel/kexec_core.c (0)
Location: include/linux/kexec.h:386
Inline: True
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
In kernel/kexec_core.c (c04101dc)
Location: include/linux/kexec.h:386
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
In kernel/kexec_core.c (0)
Location: include/linux/kexec.h:386
Inline: True
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
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f550)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff8106f550-ffffffff8106f583: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f920)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff8105f920-ffffffff8105f953: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa00)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff8106fa00-ffffffff8106fa33: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void *vaddr, unsigned int pages, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071c80)
Location: arch/x86/kernel/machine_kexec_64.c:666
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
**Symbols:**

```
ffffffff81071c80-ffffffff81071cb3: arch_kexec_post_alloc_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

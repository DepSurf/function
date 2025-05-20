# Function: <code>arch_kexec_pre_free_pages</code>

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
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810628f0)
Location: arch/x86/kernel/machine_kexec_64.c:619
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff810628f0-ffffffff81062900: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065850)
Location: arch/x86/kernel/machine_kexec_64.c:569
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81065850-ffffffff81065860: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b520)
Location: arch/x86/kernel/machine_kexec_64.c:569
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff8106b520-ffffffff8106b530: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f040)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff8106f040-ffffffff8106f06d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810705f0)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff810705f0-ffffffff8107061d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077940)
Location: arch/x86/kernel/machine_kexec_64.c:612
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81077940-ffffffff8107796d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f70)
Location: arch/x86/kernel/machine_kexec_64.c:612
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81077f70-ffffffff81077f9d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078a00)
Location: arch/x86/kernel/machine_kexec_64.c:612
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81078a00-ffffffff81078a2d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81086250)
Location: arch/x86/kernel/machine_kexec_64.c:583
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81086250-ffffffff8108627d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81096660)
Location: arch/x86/kernel/machine_kexec_64.c:592
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81096660-ffffffff8109669a: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ac3b0)
Location: arch/x86/kernel/machine_kexec_64.c:592
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff810ac3b0-ffffffff810ac3ea: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afee0)
Location: arch/x86/kernel/machine_kexec_64.c:581
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff810afee0-ffffffff810aff1a: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6a70)
Location: arch/x86/kernel/machine_kexec_64.c:578
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff810b6a70-ffffffff810b6aaa: arch_kexec_pre_free_pages (STB_GLOBAL)
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
Location: include/linux/kexec.h:390
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
In kernel/kexec_core.c (0)
Location: include/linux/kexec.h:390
Inline: True
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
Location: include/linux/kexec.h:390
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
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f590)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff8106f590-ffffffff8106f5bd: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f960)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff8105f960-ffffffff8105f98d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa40)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff8106fa40-ffffffff8106fa6d: arch_kexec_pre_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_kexec_pre_free_pages(void *vaddr, unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071cc0)
Location: arch/x86/kernel/machine_kexec_64.c:679
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_free_pages
```
**Symbols:**

```
ffffffff81071cc0-ffffffff81071ced: arch_kexec_pre_free_pages (STB_GLOBAL)
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

# Function: <code>hv_get_tsc_page</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029fe0)
Location: arch/x86/hyperv/hv_init.c:42
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81029fe0-ffffffff81029ff2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102a1e0)
Location: arch/x86/hyperv/hv_init.c:44
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8102a1e0-ffffffff8102a1f2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102aa60)
Location: arch/x86/hyperv/hv_init.c:46
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8102aa60-ffffffff8102aa72: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b0f0)
Location: arch/x86/hyperv/hv_init.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8102b0f0-ffffffff8102b102: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc7a0)
Location: drivers/clocksource/hyperv_timer.c:219
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff818bc7a0-ffffffff818bc7b2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef270)
Location: drivers/clocksource/hyperv_timer.c:218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff818ef270-ffffffff818ef282: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff82d2bf6a)
Location: drivers/clocksource/hyperv_timer.c:323
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff819c2e40-ffffffff819c2e52: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a98a)
Location: drivers/clocksource/hyperv_timer.c:323
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff819c3230-ffffffff819c3242: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff832259b9)
Location: drivers/clocksource/hyperv_timer.c:372
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff819a76a0-ffffffff819a76b2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fb93)
Location: drivers/clocksource/hyperv_timer.c:369
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81a54ba0-ffffffff81a54bb2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff834c99ca)
Location: drivers/clocksource/hyperv_timer.c:369
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81bc41b0-ffffffff81bc41c6: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69900)
Location: drivers/clocksource/hyperv_timer.c:379
Inline: True
```
**Symbols:**

```
ffffffff81d69900-ffffffff81d69916: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4df0)
Location: drivers/clocksource/hyperv_timer.c:404
Inline: False
```
**Symbols:**

```
ffffffff81dd4df0-ffffffff81dd4e06: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8cf40)
Location: drivers/clocksource/hyperv_timer.c:404
Inline: False
```
**Symbols:**

```
ffffffff81e8cf40-ffffffff81e8cf56: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890640)
Location: drivers/clocksource/hyperv_timer.c:218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81890640-ffffffff81890652: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818498c0)
Location: drivers/clocksource/hyperv_timer.c:218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff818498c0-ffffffff818498d2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e40a0)
Location: drivers/clocksource/hyperv_timer.c:218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff818e40a0-ffffffff818e40b2: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ms_hyperv_tsc_page *hv_get_tsc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900d00)
Location: drivers/clocksource/hyperv_timer.c:218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81900d00-ffffffff81900d12: hv_get_tsc_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>clear_bss</code>

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
In arch/x86/kernel/head64.c (ffffffff81f59373)
Location: arch/x86/kernel/head64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff81f81303)
Location: arch/x86/kernel/head64.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff81fbd303)
Location: arch/x86/kernel/head64.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff8209d2fe)
Location: arch/x86/kernel/head64.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff826a34ec)
Location: arch/x86/kernel/head64.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff826cc4cd)
Location: arch/x86/kernel/head64.c:346
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff828824d8)
Location: arch/x86/kernel/head64.c:362
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff82899465)
Location: arch/x86/kernel/head64.c:364
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff8289c465)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82cc253a)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae5d0)
Location: arch/x86/kernel/head64.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b85d0)
Location: arch/x86/kernel/head64.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff832986a3)
Location: arch/x86/kernel/head64.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_bss();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8344665e)
Location: arch/x86/kernel/head64.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8344665e-ffffffff8344669e: clear_bss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clear_bss();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83e5f7fd)
Location: arch/x86/kernel/head64.c:429
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff83e5f980-ffffffff83e5f9ca: clear_bss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_bss();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83694a30)
Location: arch/x86/kernel/head64.c:429
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
**Symbols:**

```
ffffffff83694a30-ffffffff83694a7a: clear_bss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_bss();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff838c4920)
Location: arch/x86/kernel/head64.c:428
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
**Symbols:**

```
ffffffff838c4920-ffffffff838c496a: clear_bss (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a465)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff82888409)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff8289d465)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
In arch/x86/kernel/head64.c (ffffffff8289d465)
Location: arch/x86/kernel/head64.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

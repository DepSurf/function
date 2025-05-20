# Function: <code>pti_set_kernel_image_nonglobal</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pti_set_kernel_image_nonglobal();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff826ef860)
Location: arch/x86/mm/pti.c:497
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81083720-ffffffff81083753: pti_set_kernel_image_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pti_set_kernel_image_nonglobal();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff828a661a)
Location: arch/x86/mm/pti.c:605
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108a230-ffffffff8108a263: pti_set_kernel_image_nonglobal (STB_GLOBAL)
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
In arch/x86/mm/pti.c (ffffffff828bebf6)
Location: arch/x86/mm/pti.c:599
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c50f0)
Location: arch/x86/mm/pti.c:601
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff82ce83fb)
Location: arch/x86/mm/pti.c:594
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff82fd5e1a)
Location: arch/x86/mm/pti.c:587
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff831e0818)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff832c3ef6)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8347680c)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff83e9f84f)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff836c39df)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff838f45cf)
Location: arch/x86/mm/pti.c:586
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828b0088)
Location: arch/x86/mm/pti.c:601
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828a8275)
Location: arch/x86/mm/pti.c:601
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c2f87)
Location: arch/x86/mm/pti.c:601
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c6110)
Location: arch/x86/mm/pti.c:601
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
</ul>

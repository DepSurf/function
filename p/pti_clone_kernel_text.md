# Function: <code>pti_clone_kernel_text</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void pti_clone_kernel_text();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81083690)
Location: arch/x86/mm/pti.c:464
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81083690-ffffffff81083711: pti_clone_kernel_text (STB_GLOBAL)
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
In arch/x86/mm/pti.c (ffffffff8108a28d)
Location: arch/x86/mm/pti.c:572
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8108dfbe)
Location: arch/x86/mm/pti.c:566
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8108ec7d)
Location: arch/x86/mm/pti.c:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pti_clone_kernel_text();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094fc0)
Location: arch/x86/mm/pti.c:561
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81094fc0-ffffffff81095044: pti_clone_kernel_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pti_clone_kernel_text();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094380)
Location: arch/x86/mm/pti.c:554
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81094380-ffffffff81094404: pti_clone_kernel_text (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff81094d64)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff810a4ce4)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff810b95d6)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff810d5146)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff810d8636)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff810e0eb6)
Location: arch/x86/mm/pti.c:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8108dc3d)
Location: arch/x86/mm/pti.c:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8107c75d)
Location: arch/x86/mm/pti.c:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8108dbed)
Location: arch/x86/mm/pti.c:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
In arch/x86/mm/pti.c (ffffffff8108ffcd)
Location: arch/x86/mm/pti.c:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
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
</ul>

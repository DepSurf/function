# Function: <code>xen_batched_set_pte</code>

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
In arch/x86/xen/mmu.c (ffffffff81021e11)
Location: arch/x86/xen/mmu.c:294
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
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
In arch/x86/xen/mmu.c (ffffffff81021401)
Location: arch/x86/xen/mmu.c:295
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff81021b71)
Location: arch/x86/xen/mmu.c:295
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff810238d1)
Location: arch/x86/xen/mmu_pv.c:262
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff81024441)
Location: arch/x86/xen/mmu_pv.c:242
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff826d5bdf)
Location: arch/x86/xen/mmu_pv.c:251
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xen_batched_set_pte(pte_t *ptep, pte_t pteval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024f90)
Location: arch/x86/xen/mmu_pv.c:260
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
**Symbols:**

```
ffffffff81024f90-ffffffff81025181: xen_batched_set_pte (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3094)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6147)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc663)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb84b1)
Location: arch/x86/xen/mmu_pv.c:249
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff831c2b0c)
Location: arch/x86/xen/mmu_pv.c:249
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3518)
Location: arch/x86/xen/mmu_pv.c:249
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8103320b)
Location: arch/x86/xen/mmu_pv.c:253
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8103abcb)
Location: arch/x86/xen/mmu_pv.c:253
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8103ac9b)
Location: arch/x86/xen/mmu_pv.c:269
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8104115b)
Location: arch/x86/xen/mmu_pv.c:269
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff82894150)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a7147)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7130)
Location: arch/x86/xen/mmu_pv.c:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

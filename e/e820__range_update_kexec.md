# Function: <code>e820__range_update_kexec</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820abebe)
Location: arch/x86/kernel/e820.c:485
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff826b2694)
Location: arch/x86/kernel/e820.c:505
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff826dbe1e)
Location: arch/x86/kernel/e820.c:507
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff82892205)
Location: arch/x86/kernel/e820.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff828a9732)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff828ac796)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd0ff5)
Location: arch/x86/kernel/e820.c:521
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff82cd0ff5-ffffffff82cd101a: e820__range_update_kexec.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbce35)
Location: arch/x86/kernel/e820.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff82fbce35-ffffffff82fbce5a: e820__range_update_kexec.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c7546)
Location: arch/x86/kernel/e820.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff831c7546-ffffffff831c756b: e820__range_update_kexec.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a843a)
Location: arch/x86/kernel/e820.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff832a843a-ffffffff832a845f: e820__range_update_kexec.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff834578b7)
Location: arch/x86/kernel/e820.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff834578b7-ffffffff834578ed: e820__range_update_kexec.constprop.0.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff83e77cf6)
Location: arch/x86/kernel/e820.c:535
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff8369a187)
Location: arch/x86/kernel/e820.c:535
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff838c9f0c)
Location: arch/x86/kernel/e820.c:535
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff8289a7a8)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff82892a66)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff828ad788)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
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
In arch/x86/kernel/e820.c (ffffffff828ad7a6)
Location: arch/x86/kernel/e820.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
</details>
</li>
</ul>

## Differences

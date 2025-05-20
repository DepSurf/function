# Function: <code>print_pte</code>

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
In arch/x86/mm/mmio-mod.c (ffffffff81074247)
Location: arch/x86/mm/mmio-mod.c:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81075825)
Location: arch/x86/mm/mmio-mod.c:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810793a5)
Location: arch/x86/mm/mmio-mod.c:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81077c76)
Location: arch/x86/mm/mmio-mod.c:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8107dfd6)
Location: arch/x86/mm/mmio-mod.c:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810810b5)
Location: arch/x86/mm/mmio-mod.c:93
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81087cc5)
Location: arch/x86/mm/mmio-mod.c:93
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b8a3)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108c513)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:81
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:die_kmmio_nesting_error
```
**Symbols:**

```
ffffffff810938e0-ffffffff8109396e: print_pte (STB_LOCAL)
ffffffff81094262-ffffffff8109428e: print_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:81
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:die_kmmio_nesting_error
```
**Symbols:**

```
ffffffff81092e30-ffffffff81092ebe: print_pte (STB_LOCAL)
ffffffff81bda053-ffffffff81bda07f: print_pte.cold (STB_LOCAL)
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
In arch/x86/mm/mmio-mod.c (ffffffff81093a6e)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810a3932)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810b802e)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810d367e)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810d6a5d)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810df28d)
Location: arch/x86/mm/mmio-mod.c:79
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b4d3)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8107a045)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b483)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108d7b2)
Location: arch/x86/mm/mmio-mod.c:81
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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

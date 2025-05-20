# Function: <code>spurious_fault_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a1b0)
Location: arch/x86/mm/fault.c:919
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
```
**Symbols:**

```
ffffffff8106a1b0-ffffffff8106a1f1: spurious_fault_check (STB_LOCAL)
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
In arch/x86/mm/fault.c (ffffffff81069f01)
Location: arch/x86/mm/fault.c:1011
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
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
In arch/x86/mm/fault.c (ffffffff8106daa1)
Location: arch/x86/mm/fault.c:1042
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
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
In arch/x86/mm/fault.c (ffffffff8106d7d1)
Location: arch/x86/mm/fault.c:1083
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81071c20)
Location: arch/x86/mm/fault.c:1062
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
```
**Symbols:**

```
ffffffff81071c20-ffffffff81071c6f: spurious_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81074a10)
Location: arch/x86/mm/fault.c:1034
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
```
**Symbols:**

```
ffffffff81074a10-ffffffff81074a5d: spurious_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>

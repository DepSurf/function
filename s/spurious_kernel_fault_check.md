# Function: <code>spurious_kernel_fault_check</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ab50)
Location: arch/x86/mm/fault.c:1102
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8107ab50-ffffffff8107ab9d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e8c0)
Location: arch/x86/mm/fault.c:1066
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8107e8c0-ffffffff8107e90d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f950)
Location: arch/x86/mm/fault.c:1088
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8107f950-ffffffff8107f99d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81086af0)
Location: arch/x86/mm/fault.c:1054
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff81086af0-ffffffff81086b3d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810873d0)
Location: arch/x86/mm/fault.c:1005
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810873d0-ffffffff8108741d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087ff0)
Location: arch/x86/mm/fault.c:967
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff81087ff0-ffffffff8108803d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81097370)
Location: arch/x86/mm/fault.c:974
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff81097370-ffffffff810973bd: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810a9a20)
Location: arch/x86/mm/fault.c:974
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810a9a20-ffffffff810a9a75: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c2e70)
Location: arch/x86/mm/fault.c:1005
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810c2e70-ffffffff810c2ec5: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c6570)
Location: arch/x86/mm/fault.c:979
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810c6570-ffffffff810c65c5: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810ce9c0)
Location: arch/x86/mm/fault.c:970
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810ce9c0-ffffffff810cea43: spurious_kernel_fault_check (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e950)
Location: arch/x86/mm/fault.c:1088
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8107e950-ffffffff8107e99d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106dd00)
Location: arch/x86/mm/fault.c:1088
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8106dd00-ffffffff8106dd4d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e900)
Location: arch/x86/mm/fault.c:1088
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff8107e900-ffffffff8107e94d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int spurious_kernel_fault_check(long unsigned int error_code, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810809f0)
Location: arch/x86/mm/fault.c:1088
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
```
**Symbols:**

```
ffffffff810809f0-ffffffff81080a3d: spurious_kernel_fault_check (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

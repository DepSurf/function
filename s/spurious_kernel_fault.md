# Function: <code>spurious_kernel_fault</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107afa0)
Location: arch/x86/mm/fault.c:1135
Inline: False
```
**Symbols:**

```
ffffffff8107afa0-ffffffff8107b1ab: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e910)
Location: arch/x86/mm/fault.c:1099
Inline: False
```
**Symbols:**

```
ffffffff8107e910-ffffffff8107eb28: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f9a0)
Location: arch/x86/mm/fault.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8107f9a0-ffffffff8107fbb8: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81086b40)
Location: arch/x86/mm/fault.c:1087
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_kern_addr_fault
```
**Symbols:**

```
ffffffff81086b40-ffffffff81086d97: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088420)
Location: arch/x86/mm/fault.c:1038
Inline: False
```
**Symbols:**

```
ffffffff81088420-ffffffff81088677: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810890d0)
Location: arch/x86/mm/fault.c:1000
Inline: False
```
**Symbols:**

```
ffffffff810890d0-ffffffff810892e9: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1007
Inline: False
```
**Symbols:**

```
ffffffff81098520-ffffffff8109874c: spurious_kernel_fault (STB_LOCAL)
ffffffff81ca0d61-ffffffff81ca0d97: spurious_kernel_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1007
Inline: False
```
**Symbols:**

```
ffffffff810ab170-ffffffff810ab39f: spurious_kernel_fault (STB_LOCAL)
ffffffff81e502ee-ffffffff81e5031e: spurious_kernel_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1038
Inline: False
```
**Symbols:**

```
ffffffff810c3510-ffffffff810c375a: spurious_kernel_fault (STB_LOCAL)
ffffffff82054999-ffffffff820549c9: spurious_kernel_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1012
Inline: False
```
**Symbols:**

```
ffffffff810c6d60-ffffffff810c6fa3: spurious_kernel_fault (STB_LOCAL)
ffffffff820d2fa7-ffffffff820d2fd7: spurious_kernel_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1003
Inline: False
```
**Symbols:**

```
ffffffff810cf220-ffffffff810cf475: spurious_kernel_fault (STB_LOCAL)
ffffffff821ade15-ffffffff821ade45: spurious_kernel_fault.cold (STB_LOCAL)
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
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e9a0)
Location: arch/x86/mm/fault.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8107e9a0-ffffffff8107ebb8: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106dd50)
Location: arch/x86/mm/fault.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8106dd50-ffffffff8106ded7: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107e950)
Location: arch/x86/mm/fault.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8107e950-ffffffff8107eb68: spurious_kernel_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spurious_kernel_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080a40)
Location: arch/x86/mm/fault.c:1121
Inline: False
```
**Symbols:**

```
ffffffff81080a40-ffffffff81080c58: spurious_kernel_fault (STB_LOCAL)
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

# Function: <code>fault_in_kernel_space</code>

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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1033
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1142
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1182
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1231
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1210
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107c221)
Location: arch/x86/mm/fault.c:1244
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff8107ff60)
Location: arch/x86/mm/fault.c:1208
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff81080ff0)
Location: arch/x86/mm/fault.c:1230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff81bbf633)
Location: arch/x86/mm/fault.c:1196
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810886f0)
Location: arch/x86/mm/fault.c:1159
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810886f0-ffffffff8108873d: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81c2a8af)
Location: arch/x86/mm/fault.c:1121
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
**Symbols:**

```
ffffffff81089360-ffffffff81089390: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81d48e99)
Location: arch/x86/mm/fault.c:1128
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
**Symbols:**

```
ffffffff810987d0-ffffffff81098800: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81f1821e)
Location: arch/x86/mm/fault.c:1128
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
**Symbols:**

```
ffffffff810ab440-ffffffff810ab47c: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff820bfa0e)
Location: arch/x86/mm/fault.c:1159
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
**Symbols:**

```
ffffffff810c4f10-ffffffff810c4f4c: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff82141711)
Location: arch/x86/mm/fault.c:1133
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
**Symbols:**

```
ffffffff810c86a0-ffffffff810c86dc: fault_in_kernel_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool fault_in_kernel_space(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff82223691)
Location: arch/x86/mm/fault.c:1138
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810d0b70-ffffffff810d0bac: fault_in_kernel_space (STB_GLOBAL)
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
In arch/x86/mm/fault.c (ffffffff8107fff0)
Location: arch/x86/mm/fault.c:1230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff8106ed70)
Location: arch/x86/mm/fault.c:1230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff8107ffa0)
Location: arch/x86/mm/fault.c:1230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/mm/fault.c (ffffffff810820a0)
Location: arch/x86/mm/fault.c:1230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>no_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ac10)
Location: arch/x86/mm/fault.c:658
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106ac10-ffffffff8106af87: no_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a970)
Location: arch/x86/mm/fault.c:715
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106a970-ffffffff8106acf8: no_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e510)
Location: arch/x86/mm/fault.c:714
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106e510-ffffffff8106e906: no_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106dc90)
Location: arch/x86/mm/fault.c:755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106dc90-ffffffff8106e09a: no_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81072ca0)
Location: arch/x86/mm/fault.c:734
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81072ca0-ffffffff810730d3: no_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:703
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81075700-ffffffff81075a9e: no_context (STB_LOCAL)
ffffffff81076536-ffffffff81076567: no_context.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:741
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107b4e0-ffffffff8107b86b: no_context (STB_LOCAL)
ffffffff8107c91c-ffffffff8107cb7a: no_context.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:707
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f010-ffffffff8107f38f: no_context (STB_LOCAL)
ffffffff81080200-ffffffff81080414: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:729
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810800a0-ffffffff8108041f: no_context (STB_LOCAL)
ffffffff810812aa-ffffffff810814be: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:693
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810872b0-ffffffff81087490: no_context (STB_LOCAL)
ffffffff810883ff-ffffffff81088428: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:640
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81087930-ffffffff81087b39: no_context (STB_LOCAL)
ffffffff81bd95df-ffffffff81bd9608: no_context.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:729
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f0a0-ffffffff8107f41f: no_context (STB_LOCAL)
ffffffff810802aa-ffffffff810804be: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:729
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106e080-ffffffff8106e3fa: no_context (STB_LOCAL)
ffffffff8106f1fa-ffffffff8106f40a: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:729
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f050-ffffffff8107f3cf: no_context (STB_LOCAL)
ffffffff8108025a-ffffffff8108046e: no_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void no_context(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int signal, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:729
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81081140-ffffffff810814bf: no_context (STB_LOCAL)
ffffffff8108237a-ffffffff8108258e: no_context.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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

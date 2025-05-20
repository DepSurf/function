# Function: <code>do_kern_addr_fault</code>

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
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ba50)
Location: arch/x86/mm/fault.c:1263
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107ba50-ffffffff8107badd: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fea0)
Location: arch/x86/mm/fault.c:1227
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107fea0-ffffffff8107ff30: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080f30)
Location: arch/x86/mm/fault.c:1249
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81080f30-ffffffff81080fc0: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088080)
Location: arch/x86/mm/fault.c:1215
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81088080-ffffffff81088100: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088680)
Location: arch/x86/mm/fault.c:1178
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81088680-ffffffff810886ee: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810892f0)
Location: arch/x86/mm/fault.c:1140
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810892f0-ffffffff8108935e: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81098750)
Location: arch/x86/mm/fault.c:1147
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81098750-ffffffff810987c2: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810ab3a0)
Location: arch/x86/mm/fault.c:1147
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810ab3a0-ffffffff810ab435: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c44d0)
Location: arch/x86/mm/fault.c:1178
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810c44d0-ffffffff810c4568: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c7d10)
Location: arch/x86/mm/fault.c:1152
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810c7d10-ffffffff810c7da8: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810d01e0)
Location: arch/x86/mm/fault.c:1157
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810d01e0-ffffffff810d0278: do_kern_addr_fault (STB_LOCAL)
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
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ff30)
Location: arch/x86/mm/fault.c:1249
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107ff30-ffffffff8107ffc0: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e610)
Location: arch/x86/mm/fault.c:1249
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106e610-ffffffff8106e6a0: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fee0)
Location: arch/x86/mm/fault.c:1249
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107fee0-ffffffff8107ff70: do_kern_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_kern_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081fd0)
Location: arch/x86/mm/fault.c:1249
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81081fd0-ffffffff8108206a: do_kern_addr_fault (STB_LOCAL)
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

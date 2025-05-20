# Function: <code>do_user_addr_fault</code>

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
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c247)
Location: arch/x86/mm/fault.c:1318
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107bd90-ffffffff8107c1da: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f800)
Location: arch/x86/mm/fault.c:1282
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107f800-ffffffff8107fc44: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080890)
Location: arch/x86/mm/fault.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81080890-ffffffff81080cd4: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087870)
Location: arch/x86/mm/fault.c:1270
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81087870-ffffffff81087cb6: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087fd0)
Location: arch/x86/mm/fault.c:1241
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81087fd0-ffffffff8108841d: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1213
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81088a80-ffffffff810890c8: do_user_addr_fault (STB_LOCAL)
ffffffff81bcb5e1-ffffffff81bcb65f: do_user_addr_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1220
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81097eb0-ffffffff81098513: do_user_addr_fault (STB_LOCAL)
ffffffff81ca0cb3-ffffffff81ca0d61: do_user_addr_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1220
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810aaaf0-ffffffff810ab16d: do_user_addr_fault (STB_LOCAL)
ffffffff81e50241-ffffffff81e502ee: do_user_addr_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1251
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810c47e0-ffffffff810c4f00: do_user_addr_fault (STB_LOCAL)
ffffffff82054a09-ffffffff82054a1d: do_user_addr_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1225
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810c7fe0-ffffffff810c868b: do_user_addr_fault (STB_LOCAL)
ffffffff820d3017-ffffffff820d302b: do_user_addr_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff810d04b0-ffffffff810d0b60: do_user_addr_fault (STB_LOCAL)
ffffffff821ade85-ffffffff821ade99: do_user_addr_fault.cold (STB_LOCAL)
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
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f890)
Location: arch/x86/mm/fault.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107f890-ffffffff8107fcd4: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e900)
Location: arch/x86/mm/fault.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106e900-ffffffff8106ed37: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f840)
Location: arch/x86/mm/fault.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107f840-ffffffff8107fc84: do_user_addr_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_user_addr_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081930)
Location: arch/x86/mm/fault.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81081930-ffffffff81081d7f: do_user_addr_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int hw_error_code</code>
</li>
</ul>
</details>
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

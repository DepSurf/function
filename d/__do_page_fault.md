# Function: <code>__do_page_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b3a0)
Location: arch/x86/mm/fault.c:1065
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
**Symbols:**

```
ffffffff8106b3a0-ffffffff8106b79a: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b1b0)
Location: arch/x86/mm/fault.c:1174
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8106b1b0-ffffffff8106b678: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106edc0)
Location: arch/x86/mm/fault.c:1214
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8106edc0-ffffffff8106f292: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e530)
Location: arch/x86/mm/fault.c:1263
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8106e530-ffffffff8106e9ef: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810735d0)
Location: arch/x86/mm/fault.c:1238
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff810735d0-ffffffff81073a9f: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81075f20)
Location: arch/x86/mm/fault.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff81075f20-ffffffff810763eb: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c1e0)
Location: arch/x86/mm/fault.c:1529
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8107c1e0-ffffffff8107c692: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ff30)
Location: arch/x86/mm/fault.c:1494
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8107ff30-ffffffff8107ffb9: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080fc0)
Location: arch/x86/mm/fault.c:1516
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff81080fc0-ffffffff81081049: __do_page_fault (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff800010da90d8)
Location: arch/arm64/mm/fault.c:409
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (c0e9f920)
Location: arch/arm/mm/fault.c:203
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __do_page_fault(struct pt_regs *regs, long unsigned int address, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000086080)
Location: arch/powerpc/mm/fault.c:436
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:do_page_fault
```
**Symbols:**

```
c000000000086080-c000000000086eb0: __do_page_fault (STB_LOCAL)
```
</details>
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
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ffc0)
Location: arch/x86/mm/fault.c:1516
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8107ffc0-ffffffff81080049: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ed40)
Location: arch/x86/mm/fault.c:1516
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8106ed40-ffffffff8106edc9: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ff70)
Location: arch/x86/mm/fault.c:1516
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff8107ff70-ffffffff8107fff9: __do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __do_page_fault(struct pt_regs *regs, long unsigned int hw_error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81082070)
Location: arch/x86/mm/fault.c:1516
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffff81082070-ffffffff810820f9: __do_page_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int hw_error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int hw_error_code</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, hw_error_code, address</code> ➡️ <code>regs, address, error_code</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
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

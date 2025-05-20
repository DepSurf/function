# Function: <code>exc_page_fault</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81bbf5e0)
Location: arch/x86/mm/fault.c:1511
Inline: False
```
**Symbols:**

```
ffffffff81bbf5e0-ffffffff81bbf780: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81c38470)
Location: arch/x86/mm/fault.c:1469
Inline: False
```
**Symbols:**

```
ffffffff81c38470-ffffffff81c385c0: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81c2a860)
Location: arch/x86/mm/fault.c:1487
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81c2a860-ffffffff81c2a9c5: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81d48e50)
Location: arch/x86/mm/fault.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81d48e50-ffffffff81d48fa5: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81f181d0)
Location: arch/x86/mm/fault.c:1496
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81f181d0-ffffffff81f18374: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff820bf9c0)
Location: arch/x86/mm/fault.c:1531
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff820bf9c0-ffffffff820bfb67: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff821416c0)
Location: arch/x86/mm/fault.c:1498
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff821416c0-ffffffff82141869: exc_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff82223640)
Location: arch/x86/mm/fault.c:1510
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff82223640-ffffffff822237e9: exc_page_fault (STB_GLOBAL)
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

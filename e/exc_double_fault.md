# Function: <code>exc_double_fault</code>

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
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbcef0)
Location: arch/x86/kernel/traps.c:344
Inline: False
```
**Symbols:**

```
ffffffff81bbcef0-ffffffff81bbd069: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c355f0)
Location: arch/x86/kernel/traps.c:349
Inline: False
```
**Symbols:**

```
ffffffff81c355f0-ffffffff81c35722: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c27a80)
Location: arch/x86/kernel/traps.c:349
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff81c27a80-ffffffff81c27bb2: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d45ad0)
Location: arch/x86/kernel/traps.c:351
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff81d45ad0-ffffffff81d45c53: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f13d90)
Location: arch/x86/kernel/traps.c:428
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff81f13d90-ffffffff81f13f4e: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820bb000)
Location: arch/x86/kernel/traps.c:437
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff820bb000-ffffffff820bb1b6: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213c720)
Location: arch/x86/kernel/traps.c:437
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff8213c720-ffffffff8213c8d6: exc_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_double_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221e720)
Location: arch/x86/kernel/traps.c:351
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_double_fault
```
**Symbols:**

```
ffffffff8221e720-ffffffff8221e8d6: exc_double_fault (STB_GLOBAL)
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

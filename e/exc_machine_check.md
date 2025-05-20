# Function: <code>exc_machine_check</code>

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
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe9c0)
Location: arch/x86/kernel/cpu/mce/core.c:1939
Inline: False
```
**Symbols:**

```
ffffffff81bbe9c0-ffffffff81bbeafd: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37240)
Location: arch/x86/kernel/cpu/mce/core.c:2015
Inline: False
```
**Symbols:**

```
ffffffff81c37240-ffffffff81c372f7: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c299a0)
Location: arch/x86/kernel/cpu/mce/core.c:2027
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81c299a0-ffffffff81c29a57: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47f10)
Location: arch/x86/kernel/cpu/mce/core.c:2090
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81d47f10-ffffffff81d47fc7: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16a10)
Location: arch/x86/kernel/cpu/mce/core.c:2106
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81f16a10-ffffffff81f16acb: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bdfe0)
Location: arch/x86/kernel/cpu/mce/core.c:2106
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff820bdfe0-ffffffff820be09b: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fa80)
Location: arch/x86/kernel/cpu/mce/core.c:2122
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff8213fa80-ffffffff8213fb3b: exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221aa0)
Location: arch/x86/kernel/cpu/mce/core.c:2151
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff82221aa0-ffffffff82221b5b: exc_machine_check (STB_GLOBAL)
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

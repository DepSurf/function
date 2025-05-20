# Function: <code>noist_exc_machine_check</code>

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
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbeb00)
Location: arch/x86/kernel/cpu/mce/core.c:1949
Inline: False
```
**Symbols:**

```
ffffffff81bbeb00-ffffffff81bbeb8c: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37300)
Location: arch/x86/kernel/cpu/mce/core.c:2025
Inline: False
```
**Symbols:**

```
ffffffff81c37300-ffffffff81c3738c: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29a60)
Location: arch/x86/kernel/cpu/mce/core.c:2037
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81c29a60-ffffffff81c29aec: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47fd0)
Location: arch/x86/kernel/cpu/mce/core.c:2100
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81d47fd0-ffffffff81d4805c: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16ad0)
Location: arch/x86/kernel/cpu/mce/core.c:2116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff81f16ad0-ffffffff81f16b99: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820be0b0)
Location: arch/x86/kernel/cpu/mce/core.c:2116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff820be0b0-ffffffff820be176: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fb50)
Location: arch/x86/kernel/cpu/mce/core.c:2132
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff8213fb50-ffffffff8213fc16: noist_exc_machine_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void noist_exc_machine_check(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221b70)
Location: arch/x86/kernel/cpu/mce/core.c:2161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_machine_check
```
**Symbols:**

```
ffffffff82221b70-ffffffff82221c36: noist_exc_machine_check (STB_GLOBAL)
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

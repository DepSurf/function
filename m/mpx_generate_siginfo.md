# Function: <code>mpx_generate_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075810)
Location: arch/x86/mm/mpx.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81075810-ffffffff81075b94: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81076d60)
Location: arch/x86/mm/mpx.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81076d60-ffffffff810770c5: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107a910)
Location: arch/x86/mm/mpx.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8107a910-ffffffff8107ac71: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81079150)
Location: arch/x86/mm/mpx.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81079150-ffffffff8107948c: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107f440)
Location: arch/x86/mm/mpx.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8107f440-ffffffff8107f640: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
siginfo_t *mpx_generate_siginfo(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81082560)
Location: arch/x86/mm/mpx.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81082560-ffffffff8108275e: mpx_generate_siginfo (STB_GLOBAL)
```
</details>
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
</ul>

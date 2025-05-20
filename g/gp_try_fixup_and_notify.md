# Function: <code>gp_try_fixup_and_notify</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool gp_try_fixup_and_notify(struct pt_regs *regs, int trapnr, long unsigned int error_code, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810425c0)
Location: arch/x86/kernel/traps.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810425c0-ffffffff81042699: gp_try_fixup_and_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool gp_try_fixup_and_notify(struct pt_regs *regs, int trapnr, long unsigned int error_code, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104bf40)
Location: arch/x86/kernel/traps.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8104bf40-ffffffff8104c019: gp_try_fixup_and_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool gp_try_fixup_and_notify(struct pt_regs *regs, int trapnr, long unsigned int error_code, const char *str, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c7b0)
Location: arch/x86/kernel/traps.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8104c7b0-ffffffff8104c88a: gp_try_fixup_and_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool gp_try_fixup_and_notify(struct pt_regs *regs, int trapnr, long unsigned int error_code, const char *str, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81053a30)
Location: arch/x86/kernel/traps.c:613
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81053a30-ffffffff81053b0a: gp_try_fixup_and_notify (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

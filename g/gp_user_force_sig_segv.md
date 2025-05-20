# Function: <code>gp_user_force_sig_segv</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gp_user_force_sig_segv(struct pt_regs *regs, int trapnr, long unsigned int error_code, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:710
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81042980-ffffffff81042a0a: gp_user_force_sig_segv (STB_LOCAL)
ffffffff81e47831-ffffffff81e4784e: gp_user_force_sig_segv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820bbeda)
Location: arch/x86/kernel/traps.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213d616)
Location: arch/x86/kernel/traps.c:720
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221f636)
Location: arch/x86/kernel/traps.c:634
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
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
</ul>

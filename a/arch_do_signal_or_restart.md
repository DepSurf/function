# Function: <code>arch_do_signal_or_restart</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs, bool has_signal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81034680)
Location: arch/x86/kernel/signal.c:785
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81034680-ffffffff81034846: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs, bool has_signal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81036210)
Location: arch/x86/kernel/signal.c:801
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81036210-ffffffff81036304: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs, bool has_signal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103b4b0)
Location: arch/x86/kernel/signal.c:861
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff8103b4b0-ffffffff8103b5a5: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81042250)
Location: arch/x86/kernel/signal.c:865
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81042250-ffffffff81042362: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b5b0)
Location: arch/x86/kernel/signal.c:302
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff8104b5b0-ffffffff8104b6c2: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104be40)
Location: arch/x86/kernel/signal.c:304
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff8104be40-ffffffff8104bf52: arch_do_signal_or_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_do_signal_or_restart(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810530c0)
Location: arch/x86/kernel/signal.c:306
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff810530c0-ffffffff810531d2: arch_do_signal_or_restart (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool has_signal</code>
</li>
</ul>
</details>
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

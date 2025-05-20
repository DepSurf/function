# Function: <code>irqentry_exit_to_user_mode</code>

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
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c38a20)
Location: kernel/entry/common.c:311
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81c38a20-ffffffff81c38a37: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2ae20)
Location: kernel/entry/common.c:312
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81c2ae20-ffffffff81c2ae37: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d493b0)
Location: kernel/entry/common.c:310
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81d493b0-ffffffff81d493c4: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f18840)
Location: kernel/entry/common.c:304
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81f18840-ffffffff81f1885a: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfe80)
Location: kernel/entry/common.c:306
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff820bfe80-ffffffff820bfe9a: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141cc0)
Location: kernel/entry/common.c:307
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff82141cc0-ffffffff82141cdf: irqentry_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irqentry_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223e00)
Location: kernel/entry/common.c:222
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff82223e00-ffffffff82224059: irqentry_exit_to_user_mode (STB_GLOBAL)
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

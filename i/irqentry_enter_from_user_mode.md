# Function: <code>irqentry_enter_from_user_mode</code>

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
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c389d0)
Location: kernel/entry/common.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81c389d0-ffffffff81c389d1: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2add0)
Location: kernel/entry/common.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81c2add0-ffffffff81c2add1: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d49360)
Location: kernel/entry/common.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81d49360-ffffffff81d49361: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f18830)
Location: kernel/entry/common.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff81f18830-ffffffff81f18835: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfe60)
Location: kernel/entry/common.c:301
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff820bfe60-ffffffff820bfe65: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141ca0)
Location: kernel/entry/common.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff82141ca0-ffffffff82141ca5: irqentry_enter_from_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irqentry_enter_from_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223d40)
Location: kernel/entry/common.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff82223d40-ffffffff82223d82: irqentry_enter_from_user_mode (STB_GLOBAL)
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

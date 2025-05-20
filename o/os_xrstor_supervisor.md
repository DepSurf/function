# Function: <code>os_xrstor_supervisor</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81053b92)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054bb4)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061632)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810626a3)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062f01)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106416a)
Location: arch/x86/kernel/fpu/xstate.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106a1f2)
Location: arch/x86/kernel/fpu/xstate.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b687)
Location: arch/x86/kernel/fpu/xstate.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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

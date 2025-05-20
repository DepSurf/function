# Function: <code>enable_single_step</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dcc9)
Location: arch/x86/kernel/step.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dae9)
Location: arch/x86/kernel/step.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103d3d9)
Location: arch/x86/kernel/step.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103b429)
Location: arch/x86/kernel/step.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103de49)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103f3e9)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810409e9)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810430a8)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043808)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enable_single_step(struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810470f0)
Location: arch/x86/kernel/step.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff810470f0-ffffffff81047175: enable_single_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enable_single_step(struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81046940)
Location: arch/x86/kernel/step.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81046940-ffffffff810469ca: enable_single_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (0)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (0)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (0)
Location: arch/x86/kernel/step.c:111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enable_single_step(struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81067740)
Location: arch/x86/kernel/step.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81067740-ffffffff8106791e: enable_single_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int enable_single_step(struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81068fe0)
Location: arch/x86/kernel/step.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81068fe0-ffffffff810691c3: enable_single_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int enable_single_step(struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81070450)
Location: arch/x86/kernel/step.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81070450-ffffffff81070633: enable_single_step (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/hw_breakpoint.c (c0316f0c)
Location: arch/arm/kernel/hw_breakpoint.c:662
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kprobes.c (c000000000056fc0)
Location: arch/powerpc/include/asm/probes.h:35
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_handler
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043988)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81032fc8)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810437c8)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81044bc8)
Location: arch/x86/kernel/step.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

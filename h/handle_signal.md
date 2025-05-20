# Function: <code>handle_signal</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e5ab)
Location: arch/x86/kernel/signal.c:632
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d553)
Location: arch/x86/kernel/signal.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d3f4)
Location: arch/x86/kernel/signal.c:702
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102b664)
Location: arch/x86/kernel/signal.c:703
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102c389)
Location: arch/x86/kernel/signal.c:704
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d647)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102e891)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030b2e)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030fae)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81033cf7)
Location: arch/x86/kernel/signal.c:706
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81034771)
Location: arch/x86/kernel/signal.c:707
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81035e60)
Location: arch/x86/kernel/signal.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff81035e60-ffffffff81035ffd: handle_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103b0e0)
Location: arch/x86/kernel/signal.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff8103b0e0-ffffffff8103b27e: handle_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81042060)
Location: arch/x86/kernel/signal.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff81042060-ffffffff81042224: handle_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b120)
Location: arch/x86/kernel/signal.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff8104b120-ffffffff8104b29c: handle_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b9c0)
Location: arch/x86/kernel/signal.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff8104b9c0-ffffffff8104bb3a: handle_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81052c40)
Location: arch/x86/kernel/signal.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
**Symbols:**

```
ffffffff81052c40-ffffffff81052dba: handle_signal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/signal.c (ffff8000100934e4)
Location: arch/arm64/kernel/signal.c:783
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030e7fc)
Location: arch/arm/kernel/signal.c:543
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void handle_signal(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b65d4)
Location: arch/riscv/kernel/signal.c:217
Inline: False
Direct callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
ffffffe0000b65d4-ffffffe0000b6854: handle_signal (STB_LOCAL)
```
</details>
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
In arch/x86/kernel/signal.c (ffffffff8103110e)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81020b2e)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030f6e)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81031dfe)
Location: arch/x86/kernel/signal.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
</ul>

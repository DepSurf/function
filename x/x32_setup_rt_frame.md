# Function: <code>x32_setup_rt_frame</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e9a5)
Location: arch/x86/kernel/signal.c:470
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
In arch/x86/kernel/signal.c (ffffffff8102d992)
Location: arch/x86/kernel/signal.c:534
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
In arch/x86/kernel/signal.c (ffffffff8102d802)
Location: arch/x86/kernel/signal.c:535
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
In arch/x86/kernel/signal.c (ffffffff8102b947)
Location: arch/x86/kernel/signal.c:536
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
In arch/x86/kernel/signal.c (ffffffff8102c66d)
Location: arch/x86/kernel/signal.c:537
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
In arch/x86/kernel/signal.c (ffffffff8102d742)
Location: arch/x86/kernel/signal.c:538
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
In arch/x86/kernel/signal.c (ffffffff8102e989)
Location: arch/x86/kernel/signal.c:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal *ksig, compat_sigset_t *set, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030580)
Location: arch/x86/kernel/signal.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81030580-ffffffff810307cc: x32_setup_rt_frame (STB_LOCAL)
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
In arch/x86/kernel/signal.c (ffffffff810310ab)
Location: arch/x86/kernel/signal.c:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal *ksig, compat_sigset_t *set, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810332a0)
Location: arch/x86/kernel/signal.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
**Symbols:**

```
ffffffff810332a0-ffffffff810335c8: x32_setup_rt_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal *ksig, compat_sigset_t *set, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81033cf0)
Location: arch/x86/kernel/signal.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
**Symbols:**

```
ffffffff81033cf0-ffffffff81034025: x32_setup_rt_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal *ksig, compat_sigset_t *set, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810357f0)
Location: arch/x86/kernel/signal.c:557
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
```
**Symbols:**

```
ffffffff810357f0-ffffffff81035b0e: x32_setup_rt_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal *ksig, compat_sigset_t *set, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103aad0)
Location: arch/x86/kernel/signal.c:562
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
```
**Symbols:**

```
ffffffff8103aad0-ffffffff8103adbe: x32_setup_rt_frame (STB_LOCAL)
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
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:563
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103120b)
Location: arch/x86/kernel/signal.c:538
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
In arch/x86/kernel/signal.c (ffffffff81020c2b)
Location: arch/x86/kernel/signal.c:538
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
In arch/x86/kernel/signal.c (ffffffff8103106b)
Location: arch/x86/kernel/signal.c:538
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
In arch/x86/kernel/signal.c (ffffffff81031f18)
Location: arch/x86/kernel/signal.c:538
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>

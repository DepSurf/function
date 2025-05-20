# Function: <code>__rseq_handle_notify_resume</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:263
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff811ea6fc-ffffffff811ea71c: __rseq_handle_notify_resume.cold.7 (STB_LOCAL)
ffffffff811ea280-ffffffff811ea6fc: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:263
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff811fb269-ffffffff811fb289: __rseq_handle_notify_resume.cold.8 (STB_LOCAL)
ffffffff811fadf0-ffffffff811fb269: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81212943-ffffffff81212965: __rseq_handle_notify_resume.cold (STB_LOCAL)
ffffffff812124e0-ffffffff81212943: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81220123-ffffffff81220145: __rseq_handle_notify_resume.cold (STB_LOCAL)
ffffffff8121fcc0-ffffffff81220123: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8124c4c0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:setup_rt_frame
```
**Symbols:**

```
ffffffff8124c4c0-ffffffff8124c527: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81256920)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81256920-ffffffff812569a2: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8125ada0)
Location: kernel/rseq.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff8125ada0-ffffffff8125ae4d: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81296b90)
Location: kernel/rseq.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
**Symbols:**

```
ffffffff81296b90-ffffffff81296c3f: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff812eccc0)
Location: kernel/rseq.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
**Symbols:**

```
ffffffff812eccc0-ffffffff812ecd2a: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81356f80)
Location: kernel/rseq.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
**Symbols:**

```
ffffffff81356f80-ffffffff81357068: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81388880)
Location: kernel/rseq.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
**Symbols:**

```
ffffffff81388880-ffffffff813888ea: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff813b22e0)
Location: kernel/rseq.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
**Symbols:**

```
ffffffff813b22e0-ffffffff813b234a: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffff8000102ac6e8)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
ffff8000102ac6e8-ffff8000102ad2e0: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (c04d99d4)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
**Symbols:**

```
c04d99d4-c04d9b44: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (c000000000360770)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
c000000000360770-c000000000360f00: __rseq_handle_notify_resume (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81218773-ffffffff81218795: __rseq_handle_notify_resume.cold (STB_LOCAL)
ffffffff81218310-ffffffff81218773: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8120b983-ffffffff8120b9a5: __rseq_handle_notify_resume.cold (STB_LOCAL)
ffffffff8120b520-ffffffff8120b983: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81216513-ffffffff81216535: __rseq_handle_notify_resume.cold (STB_LOCAL)
ffffffff812160b0-ffffffff81216513: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rseq_handle_notify_resume(struct ksignal *ksig, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff812254b0)
Location: kernel/rseq.c:262
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff812254b0-ffffffff81225599: __rseq_handle_notify_resume (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

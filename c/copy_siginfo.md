# Function: <code>copy_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b3dd)
Location: include/asm-generic/siginfo.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8108d534)
Location: include/asm-generic/siginfo.h:24
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__send_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e44d)
Location: include/linux/signal.h:35
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810916d0)
Location: include/linux/signal.h:35
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81092ff4)
Location: include/linux/signal.h:35
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81096660)
Location: include/linux/signal.h:35
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090085)
Location: include/linux/signal.h:13
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81093981)
Location: include/linux/signal.h:13
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096ef3)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109a873)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a329)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109e5f6)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2695)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810a8e33)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a732c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810aec35)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad94c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b524c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b5377)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810ba235)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b0571)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b54e4)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1af1)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810ba92f)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3be1)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810cd1de)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dce16)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
```
```
In kernel/signal.c (ffffffff810e51b2)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_siginfo(kernel_siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fd065)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810fe230)
Location: include/linux/signal.h:14
Inline: True
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
**Symbols:**

```
ffffffff810fe230-ffffffff810fe269: copy_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void copy_siginfo(kernel_siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106e00)
Location: include/linux/signal.h:14
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81109e80)
Location: include/linux/signal.h:14
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
**Symbols:**

```
ffffffff81106e00-ffffffff81106e39: copy_siginfo (STB_LOCAL)
ffffffff81109e80-ffffffff81109eb9: copy_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void copy_siginfo(kernel_siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110750)
Location: include/linux/signal.h:15
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81113820)
Location: include/linux/signal.h:15
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
**Symbols:**

```
ffffffff81110750-ffffffff81110789: copy_siginfo (STB_LOCAL)
ffffffff81113820-ffffffff81113859: copy_siginfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107758)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffff8000101114e0)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0362c68)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c0368b28)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014ea30)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (c000000000158e9c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000ccac4)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffe0000d0dfa)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7cbc)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810af5bc)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096696)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109df00)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a721c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810aeb1c)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810af4b5)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b6dc6)
Location: include/linux/signal.h:14
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

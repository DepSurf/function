# Function: <code>unhandled_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dd30)
Location: kernel/signal.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8108dd30-ffffffff8108dd6a: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090db0)
Location: kernel/signal.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81090db0-ffffffff81090def: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095d30)
Location: kernel/signal.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81095d30-ffffffff81095d6f: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092ce0)
Location: kernel/signal.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81092ce0-ffffffff81092d1d: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099bc0)
Location: kernel/signal.c:505
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81099bc0-ffffffff81099bfd: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109db90)
Location: kernel/signal.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8109db90-ffffffff8109dbcd: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5ea0)
Location: kernel/signal.c:539
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810a5ea0-ffffffff810a5edb: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aab70)
Location: kernel/signal.c:549
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810aab70-ffffffff810aabae: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1170)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b1170-ffffffff810b11ae: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba810)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810ba810-ffffffff810ba84e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5ad0)
Location: kernel/signal.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b5ad0-ffffffff810b5b0e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b76d0)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b76d0-ffffffff810b770e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c9b20)
Location: kernel/signal.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810c9b20-ffffffff810c9b5e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1580)
Location: kernel/signal.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:gp_user_force_sig_segv
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810e1580-ffffffff810e15c6: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81101840)
Location: kernel/signal.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81101840-ffffffff81101886: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110d9f0)
Location: kernel/signal.c:556
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8110d9f0-ffffffff8110da89: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117330)
Location: kernel/signal.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/cet.c:do_user_cp_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81117330-ffffffff811173c9: unhandled_signal (STB_GLOBAL)
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
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010cd48)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_show_signal
```
**Symbols:**

```
ffff80001010cd48-ffff80001010cda8: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364fc8)
Location: kernel/signal.c:554
Inline: False
```
**Symbols:**

```
c0364fc8-c0365024: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153c90)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:show_signal_msg
```
**Symbols:**

```
c000000000153c90-c000000000153ce8: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce304)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffe0000ce304-ffffffe0000ce358: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab4e0)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810ab4e0-ffffffff810ab51e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099e80)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81099e80-ffffffff81099ebe: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaa40)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810aaa40-ffffffff810aaa7e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct *tsk, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2b20)
Location: kernel/signal.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b2b20-ffffffff810b2b5e: unhandled_signal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

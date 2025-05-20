# Function: <code>force_sig_mceerr</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ffe0)
Location: kernel/signal.c:1532
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8109ffe0-ffffffff810a0072: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8330)
Location: kernel/signal.c:1618
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810a8330-ffffffff810a83b6: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1706
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b0fd2-ffffffff810b0ff3: force_sig_mceerr.cold (STB_LOCAL)
ffffffff810ae530-ffffffff810ae5bb: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4b40)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b4b40-ffffffff810b4bc3: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd800)
Location: kernel/signal.c:1707
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810bd800-ffffffff810bd876: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8b10)
Location: kernel/signal.c:1708
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b8b10-ffffffff810b8b86: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba090)
Location: kernel/signal.c:1710
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810ba090-ffffffff810ba106: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc690)
Location: kernel/signal.c:1747
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff810cc690-ffffffff810cc708: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3950)
Location: kernel/signal.c:1748
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff810e3950-ffffffff810e39e5: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81103f10)
Location: kernel/signal.c:1749
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff81103f10-ffffffff81103fa5: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110190)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff81110190-ffffffff81110225: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81119ae0)
Location: kernel/signal.c:1746
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff81119ae0-ffffffff81119b75: force_sig_mceerr (STB_GLOBAL)
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
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110c90)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_force_sig_mceerr
```
**Symbols:**

```
ffff800010110c90-ffff800010110d30: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368424)
Location: kernel/signal.c:1711
Inline: False
```
**Symbols:**

```
c0368424-c03684ec: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158530)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
c000000000158530-c0000000001585d0: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d07cc)
Location: kernel/signal.c:1711
Inline: False
```
**Symbols:**

```
ffffffe0000d07cc-ffffffe0000d0836: force_sig_mceerr (STB_GLOBAL)
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
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aeeb0)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810aeeb0-ffffffff810aef33: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d800)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8109d800-ffffffff8109d883: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae410)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810ae410-ffffffff810ae493: force_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void *addr, short int lsb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6680)
Location: kernel/signal.c:1711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b6680-ffffffff810b6703: force_sig_mceerr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *t</code>
</li>
</ul>
</details>
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

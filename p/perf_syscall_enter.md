# Function: <code>perf_syscall_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81161f20)
Location: kernel/trace/trace_syscalls.c:549
Inline: False
```
**Symbols:**

```
ffffffff81161f20-ffffffff81162107: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8116c350)
Location: kernel/trace/trace_syscalls.c:562
Inline: False
```
**Symbols:**

```
ffffffff8116c350-ffffffff8116c547: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81177760)
Location: kernel/trace/trace_syscalls.c:562
Inline: False
```
**Symbols:**

```
ffffffff81177760-ffffffff81177932: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8117a3c0)
Location: kernel/trace/trace_syscalls.c:562
Inline: False
```
**Symbols:**

```
ffffffff8117a3c0-ffffffff8117a587: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81187b90)
Location: kernel/trace/trace_syscalls.c:581
Inline: False
```
**Symbols:**

```
ffffffff81187b90-ffffffff81187df5: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81197210)
Location: kernel/trace/trace_syscalls.c:581
Inline: False
```
**Symbols:**

```
ffffffff81197210-ffffffff81197473: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a5370)
Location: kernel/trace/trace_syscalls.c:581
Inline: False
```
**Symbols:**

```
ffffffff811a5370-ffffffff811a55f0: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811b2f30-ffffffff811b3129: perf_syscall_enter (STB_LOCAL)
ffffffff811b35e0-ffffffff811b35ec: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811be360-ffffffff811be559: perf_syscall_enter (STB_LOCAL)
ffffffff811bebbf-ffffffff811bebcb: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:592
Inline: False
```
**Symbols:**

```
ffffffff811d7d20-ffffffff811d7f24: perf_syscall_enter (STB_LOCAL)
ffffffff811d8462-ffffffff811d846e: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:592
Inline: False
```
**Symbols:**

```
ffffffff811d4df0-ffffffff811d4ff0: perf_syscall_enter (STB_LOCAL)
ffffffff81be62ee-ffffffff81be62fa: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:588
Inline: False
```
**Symbols:**

```
ffffffff811d6640-ffffffff811d6840: perf_syscall_enter (STB_LOCAL)
ffffffff81bd7fba-ffffffff81bd7fc6: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:586
Inline: False
```
**Symbols:**

```
ffffffff812034d0-ffffffff812036d0: perf_syscall_enter (STB_LOCAL)
ffffffff81cb66b6-ffffffff81cb66c2: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:573
Inline: False
```
**Symbols:**

```
ffffffff8123e860-ffffffff8123ea84: perf_syscall_enter (STB_LOCAL)
ffffffff81e67687-ffffffff81e67693: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8128c270)
Location: kernel/trace/trace_syscalls.c:571
Inline: False
```
**Symbols:**

```
ffffffff8128c270-ffffffff8128c49d: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812a8ce0)
Location: kernel/trace/trace_syscalls.c:571
Inline: False
```
**Symbols:**

```
ffffffff812a8ce0-ffffffff812a8f0d: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812c49f0)
Location: kernel/trace/trace_syscalls.c:574
Inline: False
```
**Symbols:**

```
ffffffff812c49f0-ffffffff812c4c1d: perf_syscall_enter (STB_LOCAL)
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
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffff80001023dab0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffff80001023dab0-ffff80001023dca4: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c047908c)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
c047908c-c04792b4: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0000000002cd110)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
c0000000002cd110-c0000000002cd404: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffe0001930c4)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffe0001930c4-ffffffe0001931e2: perf_syscall_enter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811b6980-ffffffff811b6b79: perf_syscall_enter (STB_LOCAL)
ffffffff811b71df-ffffffff811b71eb: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811a9770-ffffffff811a9969: perf_syscall_enter (STB_LOCAL)
ffffffff811a9fcf-ffffffff811a9fdb: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811b4750-ffffffff811b4949: perf_syscall_enter (STB_LOCAL)
ffffffff811b4faf-ffffffff811b4fbb: perf_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void perf_syscall_enter(void *ignore, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:583
Inline: False
```
**Symbols:**

```
ffffffff811c27f0-ffffffff811c29e9: perf_syscall_enter (STB_LOCAL)
ffffffff811c304f-ffffffff811c305b: perf_syscall_enter.cold (STB_LOCAL)
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

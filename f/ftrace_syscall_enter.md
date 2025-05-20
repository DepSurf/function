# Function: <code>ftrace_syscall_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81162110)
Location: kernel/trace/trace_syscalls.c:294
Inline: False
```
**Symbols:**

```
ffffffff81162110-ffffffff811623a6: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8116c850)
Location: kernel/trace/trace_syscalls.c:307
Inline: False
```
**Symbols:**

```
ffffffff8116c850-ffffffff8116cb32: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81177b40)
Location: kernel/trace/trace_syscalls.c:307
Inline: False
```
**Symbols:**

```
ffffffff81177b40-ffffffff81177e0a: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8117a7d0)
Location: kernel/trace/trace_syscalls.c:307
Inline: False
```
**Symbols:**

```
ffffffff8117a7d0-ffffffff8117ab08: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81188040)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff81188040-ffffffff81188370: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81196d50)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff81196d50-ffffffff81197024: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a4e90)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811a4e90-ffffffff811a517d: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811b2c40-ffffffff811b2f26: ftrace_syscall_enter (STB_LOCAL)
ffffffff811b35d4-ffffffff811b35e0: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811be070-ffffffff811be356: ftrace_syscall_enter (STB_LOCAL)
ffffffff811bebb3-ffffffff811bebbf: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:293
Inline: False
```
**Symbols:**

```
ffffffff811d76c0-ffffffff811d79a1: ftrace_syscall_enter (STB_LOCAL)
ffffffff811d8445-ffffffff811d8451: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:293
Inline: False
```
**Symbols:**

```
ffffffff811d4790-ffffffff811d4a71: ftrace_syscall_enter (STB_LOCAL)
ffffffff81be62d1-ffffffff81be62dd: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:293
Inline: False
```
**Symbols:**

```
ffffffff811d6000-ffffffff811d62ce: ftrace_syscall_enter (STB_LOCAL)
ffffffff81bd7f9d-ffffffff81bd7fa9: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:293
Inline: False
```
**Symbols:**

```
ffffffff81202c00-ffffffff81202ef5: ftrace_syscall_enter (STB_LOCAL)
ffffffff81cb6688-ffffffff81cb6694: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:293
Inline: False
```
**Symbols:**

```
ffffffff8123ea90-ffffffff8123eca6: ftrace_syscall_enter (STB_LOCAL)
ffffffff81e67693-ffffffff81e6769f: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8128c4b0)
Location: kernel/trace/trace_syscalls.c:291
Inline: False
```
**Symbols:**

```
ffffffff8128c4b0-ffffffff8128c6d2: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812a93c0)
Location: kernel/trace/trace_syscalls.c:291
Inline: False
```
**Symbols:**

```
ffffffff812a93c0-ffffffff812a95e0: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812c50d0)
Location: kernel/trace/trace_syscalls.c:291
Inline: False
```
**Symbols:**

```
ffffffff812c50d0-ffffffff812c52f0: ftrace_syscall_enter (STB_LOCAL)
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
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffff80001023dca8)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffff80001023dca8-ffff80001023df14: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c04792b4)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
c04792b4-c0479538: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0000000002cd410)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
c0000000002cd410-c0000000002cd804: ftrace_syscall_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffe00019377c)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffe00019377c-ffffffe000193956: ftrace_syscall_enter (STB_LOCAL)
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
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811b6690-ffffffff811b6976: ftrace_syscall_enter (STB_LOCAL)
ffffffff811b71d3-ffffffff811b71df: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811a9490-ffffffff811a976f: ftrace_syscall_enter (STB_LOCAL)
ffffffff811a9fc3-ffffffff811a9fcf: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811b4460-ffffffff811b4746: ftrace_syscall_enter (STB_LOCAL)
ffffffff811b4fa3-ffffffff811b4faf: ftrace_syscall_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ftrace_syscall_enter(void *data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:308
Inline: False
```
**Symbols:**

```
ffffffff811c2500-ffffffff811c27e6: ftrace_syscall_enter (STB_LOCAL)
ffffffff811c3043-ffffffff811c304f: ftrace_syscall_enter.cold (STB_LOCAL)
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

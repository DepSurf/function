# Function: <code>__traceiter_sys_enter</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b110)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff8113b110-ffffffff8113b157: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113c400)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff8113c400-ffffffff8113c445: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115f520)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff8115f520-ffffffff8115f565: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81189950)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81189950-ffffffff8118999f: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c5dd0)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff811c5dd0-ffffffff811c5e1f: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d89b0)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff811d89b0-ffffffff811d89ff: __traceiter_sys_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811ee4c0)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff811ee4c0-ffffffff811ee50f: __traceiter_sys_enter (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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

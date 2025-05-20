# Function: <code>__traceiter_sys_exit</code>

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
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b160)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff8113b160-ffffffff8113b1a7: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113c450)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff8113c450-ffffffff8113c495: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115f570)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff8115f570-ffffffff8115f5b5: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811899a0)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff811899a0-ffffffff811899ef: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c5e30)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff811c5e30-ffffffff811c5e7f: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d8a30)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff811d8a30-ffffffff811d8a7f: __traceiter_sys_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sys_exit(void *__data, struct pt_regs *regs, long int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811ee540)
Location: include/trace/events/syscalls.h:44
Inline: False
```
**Symbols:**

```
ffffffff811ee540-ffffffff811ee58f: __traceiter_sys_exit (STB_GLOBAL)
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

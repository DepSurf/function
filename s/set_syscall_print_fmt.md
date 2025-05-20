# Function: <code>set_syscall_print_fmt</code>

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
In kernel/trace/trace_syscalls.c (ffffffff81f853c7)
Location: kernel/trace/trace_syscalls.c:223
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff81fae9b2)
Location: kernel/trace/trace_syscalls.c:234
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff81feafd9)
Location: kernel/trace/trace_syscalls.c:234
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff820cba0a)
Location: kernel/trace/trace_syscalls.c:234
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff826d4079)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff826fe83a)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828b5754)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828ce6ad)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828d6c0b)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_syscall_print_fmt(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff82cf66e7)
Location: kernel/trace/trace_syscalls.c:239
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff82cf66e7-ffffffff82cf6752: set_syscall_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_syscall_print_fmt(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff82fe31d8)
Location: kernel/trace/trace_syscalls.c:239
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff82fe31d8-ffffffff82fe3243: set_syscall_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff831ed9b4)
Location: kernel/trace/trace_syscalls.c:239
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff832d262b)
Location: kernel/trace/trace_syscalls.c:239
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff834869d5)
Location: kernel/trace/trace_syscalls.c:239
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff83eb5f25)
Location: kernel/trace/trace_syscalls.c:237
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff836db315)
Location: kernel/trace/trace_syscalls.c:237
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8390d885)
Location: kernel/trace/trace_syscalls.c:237
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffff80001144f4c4)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (c1529b7c)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c000000001376500)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffe00000f8ea)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828bfabc)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828b815c)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828d283f)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
In kernel/trace/trace_syscalls.c (ffffffff828d7c60)
Location: kernel/trace/trace_syscalls.c:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
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
</ul>

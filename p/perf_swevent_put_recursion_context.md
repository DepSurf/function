# Function: <code>perf_swevent_put_recursion_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81182d9a)
Location: kernel/events/core.c:6696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
```
**Symbols:**

```
ffffffff81184540-ffffffff8118455d: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118b358)
Location: kernel/events/core.c:7290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811962b0-ffffffff811962cd: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119abe8)
Location: kernel/events/core.c:7403
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811a5d30-ffffffff811a5d4d: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a261b)
Location: kernel/events/core.c:7626
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811ad4c0-ffffffff811ad4dd: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6773)
Location: kernel/events/core.c:7623
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811c1030-ffffffff811c104d: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d6260)
Location: kernel/events/core.c:8005
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811e13d0-ffffffff811e13ed: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6e03)
Location: kernel/events/core.c:8014
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811f1830-ffffffff811f184d: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe0f2)
Location: kernel/events/core.c:8318
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff812093e0-ffffffff812093f8: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b3a2)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff81216750-ffffffff81216768: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812373f8)
Location: kernel/events/core.c:8984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff81242660-ffffffff81242678: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240ffd)
Location: kernel/events/core.c:9250
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8124ce50-ffffffff8124ce68: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244db6)
Location: kernel/events/core.c:9380
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff812514b0-ffffffff812514c8: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127fdc5)
Location: kernel/events/core.c:9499
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8128c2b0-ffffffff8128c2c8: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4e62)
Location: kernel/events/core.c:9434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff812e0e00-ffffffff812e0e2a: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133d624)
Location: kernel/events/core.c:9759
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff813492f0-ffffffff8134931a: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136e7f2)
Location: kernel/events/core.c:9788
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_events_user.c:user_event_perf
```
**Symbols:**

```
ffffffff8137a2f0-ffffffff8137a31a: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813978e2)
Location: kernel/events/core.c:9858
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_events_user.c:user_event_perf
```
**Symbols:**

```
ffffffff813a34f0-ffffffff813a351a: perf_swevent_put_recursion_context (STB_GLOBAL)
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
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a09c8)
Location: kernel/events/core.c:8434
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffff8000102a09c8-ffff8000102a09f0: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d0ad8)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
c04d0cf8-c04d0d28: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000035259c)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
c000000000352890-c0000000003528c0: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5dc2)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffe0001cfd90-ffffffe0001cfdc8: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812039c2)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8120eda0-ffffffff8120edb8: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6ac2)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff81201b50-ffffffff81201b68: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201792)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8120cb40-ffffffff8120cb58: perf_swevent_put_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_swevent_put_recursion_context(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210b1c)
Location: kernel/events/core.c:8434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8121b9c0-ffffffff8121b9d8: perf_swevent_put_recursion_context (STB_GLOBAL)
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

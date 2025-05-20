# Function: <code>stack_trace_save_user</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811260e0)
Location: kernel/stacktrace.c:222
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811260e0-ffffffff81126189: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811320b0)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811320b0-ffffffff81132159: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811414f0)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_userstack
```
**Symbols:**

```
ffffffff811414f0-ffffffff811415c6: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d790)
Location: kernel/stacktrace.c:221
Inline: False
```
**Symbols:**

```
ffffffff8113d790-ffffffff8113d80d: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e9e0)
Location: kernel/stacktrace.c:221
Inline: False
```
**Symbols:**

```
ffffffff8113e9e0-ffffffff8113ea5d: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161e70)
Location: kernel/stacktrace.c:221
Inline: False
```
**Symbols:**

```
ffffffff81161e70-ffffffff81161eed: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194d80)
Location: kernel/stacktrace.c:222
Inline: False
```
**Symbols:**

```
ffffffff81194d80-ffffffff81194e03: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d2a90)
Location: kernel/stacktrace.c:222
Inline: False
```
**Symbols:**

```
ffffffff811d2a90-ffffffff811d2b13: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6d80)
Location: kernel/stacktrace.c:222
Inline: False
```
**Symbols:**

```
ffffffff811e6d80-ffffffff811e6e03: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fcad0)
Location: kernel/stacktrace.c:223
Inline: False
```
**Symbols:**

```
ffffffff811fcad0-ffffffff811fcb53: stack_trace_save_user (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a860)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8112a860-ffffffff8112a909: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111d0d0)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8111d0d0-ffffffff8111d179: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128580)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81128580-ffffffff81128629: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int stack_trace_save_user(long unsigned int *store, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134c10)
Location: kernel/stacktrace.c:223
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81134c10-ffffffff81134cb9: stack_trace_save_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

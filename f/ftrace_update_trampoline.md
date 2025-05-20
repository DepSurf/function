# Function: <code>ftrace_update_trampoline</code>

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
In kernel/trace/ftrace.c (ffffffff81144f84)
Location: kernel/trace/ftrace.c:5025
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff8114de65)
Location: kernel/trace/ftrace.c:5112
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff81157da5)
Location: kernel/trace/ftrace.c:5161
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff8115b0a1)
Location: kernel/trace/ftrace.c:5904
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff81168191)
Location: kernel/trace/ftrace.c:6209
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff81176eb5)
Location: kernel/trace/ftrace.c:6195
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
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
In kernel/trace/ftrace.c (ffffffff81184b05)
Location: kernel/trace/ftrace.c:6155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff811918d0)
Location: kernel/trace/ftrace.c:6203
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff8119d900)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b3e6c)
Location: kernel/trace/ftrace.c:6734
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0d30)
Location: kernel/trace/ftrace.c:6887
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff811b0d30-ffffffff811b0dcc: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1780)
Location: kernel/trace/ftrace.c:6892
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff811b1780-ffffffff811b181c: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811db620)
Location: kernel/trace/ftrace.c:6893
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff811db620-ffffffff811db6bc: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211690)
Location: kernel/trace/ftrace.c:7338
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff81211690-ffffffff8121174e: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125ac30)
Location: kernel/trace/ftrace.c:7454
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8125ac30-ffffffff8125acee: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812720d0)
Location: kernel/trace/ftrace.c:7269
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff812720d0-ffffffff8127218e: ftrace_update_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128c5c0)
Location: kernel/trace/ftrace.c:7269
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8128c5c0-ffffffff8128c67e: ftrace_update_trampoline (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff8000102167ec)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (c04555a0)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (c0000000002987e8)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffe0001762c6)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff81195f20)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff81189030)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff81193cf0)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
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
In kernel/trace/ftrace.c (ffffffff811a18c0)
Location: kernel/trace/ftrace.c:6236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
</details>
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

# Function: <code>lock_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127ad60)
Location: fs/proc/base.c:443
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8127ad60-ffffffff8127adbb: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a7820)
Location: fs/proc/base.c:443
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff812a7820-ffffffff812a787b: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bd0e0)
Location: fs/proc/base.c:429
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff812bd0e0-ffffffff812bd13b: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ca2a0)
Location: fs/proc/base.c:406
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff812ca2a0-ffffffff812ca2fb: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812eeb30)
Location: fs/proc/base.c:407
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff812eeb30-ffffffff812eeb8b: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131bb30)
Location: fs/proc/base.c:382
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8131bb30-ffffffff8131bb8b: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81332cc0)
Location: fs/proc/base.c:386
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81332cc0-ffffffff81332d1b: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ac40)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8135ac40-ffffffff8135ac9d: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81372e50)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81372e50-ffffffff81372ead: lock_trace (STB_LOCAL)
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
In fs/proc/base.c (ffffffff813bb2bb)
Location: fs/proc/base.c:406
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cce4b)
Location: fs/proc/base.c:406
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff813d3d1b)
Location: fs/proc/base.c:403
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff8142542b)
Location: fs/proc/base.c:407
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff8149ecd8)
Location: fs/proc/base.c:406
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff81533a48)
Location: fs/proc/base.c:407
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff8156bc38)
Location: fs/proc/base.c:408
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
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
In fs/proc/base.c (ffffffff815a43a8)
Location: fs/proc/base.c:408
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_stack
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043d360)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffff80001043d360-ffff80001043d3c4: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0603490)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
c0603490-c06034ec: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000551790)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
c000000000551790-c000000000551820: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d6666)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffe0002d6666-ffffffe0002d66c2: lock_trace (STB_LOCAL)
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
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136b430)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8136b430-ffffffff8136b48d: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135bec0)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8135bec0-ffffffff8135bf1d: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81368f00)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81368f00-ffffffff81368f5d: lock_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lock_trace(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137c770)
Location: fs/proc/base.c:404
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8137c770-ffffffff8137c7cd: lock_trace (STB_LOCAL)
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

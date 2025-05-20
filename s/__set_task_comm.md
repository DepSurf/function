# Function: <code>__set_task_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81213d00)
Location: fs/exec.c:1085
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff81213d00-ffffffff81213da8: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123aa60)
Location: fs/exec.c:1232
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8123aa60-ffffffff8123ab01: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124d810)
Location: fs/exec.c:1239
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8124d810-ffffffff8124d8b1: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812597d0)
Location: fs/exec.c:1265
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812597d0-ffffffff81259871: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127ba30)
Location: fs/exec.c:1245
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8127ba30-ffffffff8127bad4: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a27d0)
Location: fs/exec.c:1249
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812a27d0-ffffffff812a2874: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b8480)
Location: fs/exec.c:1253
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812b8480-ffffffff812b8524: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d5010)
Location: fs/exec.c:1254
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812d5010-ffffffff812d50b4: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e6ba0)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812e6ba0-ffffffff812e6c44: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131e1f0)
Location: fs/exec.c:1320
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8131e1f0-ffffffff8131e294: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81329700)
Location: fs/exec.c:1232
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff81329700-ffffffff8132984c: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132f540)
Location: fs/exec.c:1224
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8132f540-ffffffff8132f690: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137ccf0)
Location: fs/exec.c:1224
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff8137ccf0-ffffffff8137ce40: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fca20)
Location: fs/exec.c:1232
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff813fca20-ffffffff813fcacf: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81486580)
Location: fs/exec.c:1227
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81486580-ffffffff8148662f: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814bb230)
Location: fs/exec.c:1230
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff814bb230-ffffffff814bb2df: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ed7a0)
Location: fs/exec.c:1245
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - fs/exec.c:begin_new_exec
  - fs/proc/base.c:comm_write
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff814ed7a0-ffffffff814ed84f: __set_task_comm (STB_GLOBAL)
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
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038ef68)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffff80001038ef68-ffff80001038f084: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0576070)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
c0576070-c0576154: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486b00)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
c000000000486b00-c000000000486c50: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025f07c)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffe00025f07c-ffffffe00025f16c: __set_task_comm (STB_GLOBAL)
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
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812df180)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812df180-ffffffff812df224: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cfdc0)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812cfdc0-ffffffff812cfe64: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dcf90)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812dcf90-ffffffff812dd034: __set_task_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_task_comm(struct task_struct *tsk, const char *buf, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812edf10)
Location: fs/exec.c:1255
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/workqueue.c:worker_thread
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - fs/exec.c:setup_new_exec
  - fs/proc/base.c:comm_write
```
**Symbols:**

```
ffffffff812edf10-ffffffff812edfce: __set_task_comm (STB_GLOBAL)
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

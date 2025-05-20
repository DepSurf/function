# Function: <code>kthread_park</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0210)
Location: kernel/kthread.c:457
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - kernel/watchdog.c:watchdog_park_threads
```
**Symbols:**

```
ffffffff810a0210-ffffffff810a0263: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3900)
Location: kernel/kthread.c:457
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - kernel/watchdog.c:watchdog_park_threads
```
**Symbols:**

```
ffffffff810a3900-ffffffff810a3953: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a89d0)
Location: kernel/kthread.c:485
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - kernel/watchdog.c:watchdog_park_threads
```
**Symbols:**

```
ffffffff810a89d0-ffffffff810a8a59: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a57e0)
Location: kernel/kthread.c:489
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - kernel/watchdog.c:watchdog_park_threads
```
**Symbols:**

```
ffffffff810a57e0-ffffffff810a5839: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abef0)
Location: kernel/kthread.c:496
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810abef0-ffffffff810abf49: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b39b0)
Location: kernel/kthread.c:507
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810b39b0-ffffffff810b3a21: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bccb0)
Location: kernel/kthread.c:506
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810bccb0-ffffffff810bcd32: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810c327b-ffffffff810c32ab: kthread_park.cold (STB_LOCAL)
ffffffff810c1cd0-ffffffff810c1d4d: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8220)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810c8220-ffffffff810c82af: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d08d0)
Location: kernel/kthread.c:551
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
```
**Symbols:**

```
ffffffff810d08d0-ffffffff810d095f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb4b0)
Location: kernel/kthread.c:577
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_uring_cancel_task_requests
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io_uring.c:io_sq_thread_stop
```
**Symbols:**

```
ffffffff810cb4b0-ffffffff810cb53f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccc40)
Location: kernel/kthread.c:604
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810ccc40-ffffffff810ccccf: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df9e0)
Location: kernel/kthread.c:604
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810df9e0-ffffffff810dfa6f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9820)
Location: kernel/kthread.c:664
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff810f9820-ffffffff810f98c1: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c4f0)
Location: kernel/kthread.c:664
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff8111c4f0-ffffffff8111c591: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129740)
Location: kernel/kthread.c:665
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff81129740-ffffffff811297e1: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133d80)
Location: kernel/kthread.c:664
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/stop_machine.c:stop_machine_park
```
**Symbols:**

```
ffffffff81133d80-ffffffff81133e21: kthread_park (STB_GLOBAL)
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
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101276e0)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffff8000101276e0-ffff8000101277a0: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379c7c)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
c0379c7c-c0379dc8: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171a60)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
c000000000171a60-c000000000171b6c: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000debb4)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffe0000debb4-ffffffe0000dec4c: kthread_park (STB_GLOBAL)
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
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c25a0)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810c25a0-ffffffff810c262f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0df0)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810b0df0-ffffffff810b0e7f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1af0)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810c1af0-ffffffff810c1b7f: kthread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kthread_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9f20)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/smpboot.c:smpboot_park_threads
  - kernel/stop_machine.c:stop_machine_park
  - fs/io_uring.c:io_finish_async
```
**Symbols:**

```
ffffffff810c9f20-ffffffff810c9faf: kthread_park (STB_GLOBAL)
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

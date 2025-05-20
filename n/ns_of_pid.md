# Function: <code>ns_of_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f4b0)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff8109db39)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff8132bfec)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108165e)
Location: include/linux/pid.h:134
Inline: True
```
```
In kernel/pid.c (ffffffff810a1440)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81360c7c)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810860a1)
Location: include/linux/pid.h:134
Inline: True
```
```
In kernel/pid.c (ffffffff810a6500)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff813775fc)
Location: include/linux/pid.h:134
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082854)
Location: include/linux/pid.h:136
Inline: True
```
```
In kernel/pid.c (ffffffff810a3482)
Location: include/linux/pid.h:136
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff8138b15d)
Location: include/linux/pid.h:136
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81089690)
Location: include/linux/pid.h:135
Inline: True
```
```
In kernel/pid.c (ffffffff810a9d13)
Location: include/linux/pid.h:135
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff813b04dd)
Location: include/linux/pid.h:135
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108d03e)
Location: include/linux/pid.h:135
Inline: True
```
```
In kernel/pid.c (ffffffff810b087f)
Location: include/linux/pid.h:135
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff813e051f)
Location: include/linux/pid.h:135
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094b5a)
Location: include/linux/pid.h:128
Inline: True
```
```
In kernel/pid.c (ffffffff810b99b1)
Location: include/linux/pid.h:128
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff813fad1d)
Location: include/linux/pid.h:128
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109930e)
Location: include/linux/pid.h:133
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810afef8)
Location: include/linux/pid.h:133
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810bf7b9)
Location: include/linux/pid.h:133
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81427139)
Location: include/linux/pid.h:133
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f908)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b6509)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810c5b8b)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81440e79)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a69c1)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810be6f8)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810cd411)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81491c2b)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a24d7)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b99f8)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810c7fbc)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff814af95d)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a31ca)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810bb1e8)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810c9a5c)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff814b579d)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b496e)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810cdaf8)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810dc9c9)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff8150de8d)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cae69)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810e5c94)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810f755f)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff815a0962)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e83a0)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81106854)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff81119cdf)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff8164a2f2)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f4000)
Location: include/linux/pid.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81112b44)
Location: include/linux/pid.h:152
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff81125df0)
Location: include/linux/pid.h:152
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81682839)
Location: include/linux/pid.h:152
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fd3c2)
Location: include/linux/pid.h:143
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8111c534)
Location: include/linux/pid.h:143
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff811303f0)
Location: include/linux/pid.h:143
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff816bec39)
Location: include/linux/pid.h:143
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3f6c)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff800010112878)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffff8000101240b4)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffff80001052995c)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352994)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c03697f4)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/pid.c (c0377400)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
```
```
In ipc/mqueue.c (c06e3bdc)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a308)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c00000000015a284)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/pid.c (c00000000016de08)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (c000000000675434)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0742)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000d1786)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffe0000dc3de)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffe00038c832)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099228)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b0879)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810bff0b)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81439459)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087c78)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109f199)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810ae71b)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff81429ec9)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810991d8)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810afdd9)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810bf45b)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff814355f9)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0e11)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b80a9)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/pid.c (ffffffff810c78d9)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In ipc/mqueue.c (ffffffff8144cc9e)
Location: include/linux/pid.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>

## Differences

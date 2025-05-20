# Function: <code>perf_event_ctx_unlock</code>

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
In kernel/events/core.c (ffffffff8117b3ee)
Location: kernel/events/core.c:986
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff81191a43)
Location: kernel/events/core.c:1231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811a3957)
Location: kernel/events/core.c:1239
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811aafd4)
Location: kernel/events/core.c:1231
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811be8f0)
Location: kernel/events/core.c:1274
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811dea23)
Location: kernel/events/core.c:1297
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811eee3a)
Location: kernel/events/core.c:1297
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff812066ef)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff81213a76)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8123fd60)
Location: kernel/events/core.c:1361
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8124a319)
Location: kernel/events/core.c:1379
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8124e21b)
Location: kernel/events/core.c:1377
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff81288f8a)
Location: kernel/events/core.c:1408
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff812ddf94)
Location: kernel/events/core.c:1317
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8133ae7d)
Location: kernel/events/core.c:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8136bd5d)
Location: kernel/events/core.c:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff81394f1a)
Location: kernel/events/core.c:1301
Inline: True
Inline callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffff80001029dc30)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (c04cd274)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (c00000000034e81c)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffe0001cbb66)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff8120c0c6)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff811fee96)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff81209e66)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
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
In kernel/events/core.c (ffffffff81218c40)
Location: kernel/events/core.c:1299
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
</details>
</li>
</ul>

## Differences

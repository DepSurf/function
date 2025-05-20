# Function: <code>perf_event_ctx_lock</code>

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
In kernel/events/core.c (ffffffff8117dada)
Location: kernel/events/core.c:981
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
In kernel/events/core.c (ffffffff81191a29)
Location: kernel/events/core.c:1226
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
In kernel/events/core.c (ffffffff811a11d9)
Location: kernel/events/core.c:1234
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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a8aa5)
Location: kernel/events/core.c:1226
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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bc2fd)
Location: kernel/events/core.c:1269
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff811dc4ad)
Location: kernel/events/core.c:1292
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff811ec8ad)
Location: kernel/events/core.c:1292
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81204295)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81210e85)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8123ce4c)
Location: kernel/events/core.c:1356
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8124707c)
Location: kernel/events/core.c:1374
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8124af2c)
Location: kernel/events/core.c:1372
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8128451c)
Location: kernel/events/core.c:1403
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff812d893d)
Location: kernel/events/core.c:1312
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81340edd)
Location: kernel/events/core.c:1285
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81371e6d)
Location: kernel/events/core.c:1285
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8139b1dd)
Location: kernel/events/core.c:1296
Inline: True
Inline callers:
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
In kernel/events/core.c (ffff80001029b380)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (c04ca81c)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (c00000000034b120)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffe0001cd94c)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff812094d5)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff811fc285)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81207275)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff81215ff5)
Location: kernel/events/core.c:1294
Inline: True
Inline callers:
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

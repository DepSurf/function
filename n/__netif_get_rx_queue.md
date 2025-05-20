# Function: <code>__netif_get_rx_queue</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3314
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3530
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3547
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
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
In net/bpf/test_run.c (ffffffff81a7effb)
Location: include/linux/netdevice.h:3674
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81a88a7b)
Location: include/linux/netdevice.h:3835
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81a71cb5)
Location: include/linux/netdevice.h:3920
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81b2b428)
Location: include/linux/netdevice.h:3934
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81cb572a)
Location: include/linux/netdevice.h:3725
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81e73bfa)
Location: include/linux/netdevice.h:3770
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffff81ecf968)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/core/dev.c (ffffffff81eec754)
Location: include/net/netdev_rx_queue.h:41
Inline: True
Inline callers:
  - net/core/dev.c:netif_queue_set_napi
```
```
In net/core/netdev-genl.c (ffffffff81f3d2d4)
Location: include/net/netdev_rx_queue.h:41
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
```
```
In net/bpf/test_run.c (ffffffff81f932b8)
Location: include/net/netdev_rx_queue.h:41
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
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
In net/bpf/test_run.c (c0d63354)
Location: include/linux/netdevice.h:3561
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (c000000000d530a0)
Location: include/linux/netdevice.h:3561
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (ffffffe0007be11c)
Location: include/linux/netdevice.h:3561
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
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
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3561
Inline: True
```
</details>
</li>
</ul>

## Differences

# Function: <code>xdp_release_frame</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3db8)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff81200b58)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff81227db2)
Location: include/net/xdp.h:173
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff8122eb12)
Location: include/net/xdp.h:220
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
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
In net/core/xdp.c (ffffffff81a1f986)
Location: include/net/xdp.h:245
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/xdp.c (ffffffff81ad3946)
Location: include/net/xdp.h:246
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/xdp.c (ffffffff81c5130f)
Location: include/net/xdp.h:323
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/xdp.c (ffffffff81e06aab)
Location: include/net/xdp.h:323
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/bpf/cpumap.c (ffff800010288238)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (c04b8508)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (c0000000003338e0)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffe0001bce38)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff811f9178)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff811ebec8)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff811f6f48)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
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
In kernel/bpf/cpumap.c (ffffffff8120522e)
Location: include/net/xdp.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
</details>
</li>
</ul>

## Differences

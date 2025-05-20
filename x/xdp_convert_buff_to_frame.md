# Function: <code>xdp_convert_buff_to_frame</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81227884)
Location: include/net/xdp.h:126
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff812287e5)
Location: include/net/xdp.h:126
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8188cba1)
Location: include/net/xdp.h:126
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
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
In kernel/bpf/devmap.c (ffffffff8122e3d4)
Location: include/net/xdp.h:189
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8122f6e3)
Location: include/net/xdp.h:189
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8189adf8)
Location: include/net/xdp.h:189
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff818a8a56)
Location: include/net/xdp.h:189
Inline: True
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
In kernel/bpf/devmap.c (ffffffff81233240)
Location: include/net/xdp.h:214
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff812344e3)
Location: include/net/xdp.h:214
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8187d658)
Location: include/net/xdp.h:214
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8188bbb9)
Location: include/net/xdp.h:214
Inline: True
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
In kernel/bpf/devmap.c (ffffffff8126c88d)
Location: include/net/xdp.h:215
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8126e4b5)
Location: include/net/xdp.h:215
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8190ecd5)
Location: include/net/xdp.h:215
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8191eb43)
Location: include/net/xdp.h:215
Inline: True
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
In drivers/net/tun.c (ffffffff81a62481)
Location: include/net/xdp.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81a73dac)
Location: include/net/xdp.h:290
Inline: True
```
```
In net/core/filter.c (ffffffff81c4be83)
Location: include/net/xdp.h:290
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
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
In drivers/net/tun.c (ffffffff81becc21)
Location: include/net/xdp.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81c07e6d)
Location: include/net/xdp.h:290
Inline: True
```
```
In net/core/filter.c (ffffffff81e00be3)
Location: include/net/xdp.h:290
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
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
In drivers/net/tun.c (ffffffff81c45121)
Location: include/net/xdp.h:294
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81c4f83e)
Location: include/net/xdp.h:294
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d4fb)
Location: include/net/xdp.h:294
Inline: True
```
```
In net/core/filter.c (ffffffff81e72704)
Location: include/net/xdp.h:294
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
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
In drivers/net/tun.c (ffffffff81cfa370)
Location: include/net/xdp.h:293
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81d05428)
Location: include/net/xdp.h:293
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d21e4b)
Location: include/net/xdp.h:293
Inline: True
```
```
In net/core/filter.c (ffffffff81f31df9)
Location: include/net/xdp.h:293
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

# Function: <code>xdp_update_frame_from_buff</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122e3e6)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8122f6fc)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8189ae09)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff818a8a6e)
Location: include/net/xdp.h:160
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
In kernel/bpf/devmap.c (ffffffff81233252)
Location: include/net/xdp.h:185
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff812344fc)
Location: include/net/xdp.h:185
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8187d669)
Location: include/net/xdp.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8188bbd1)
Location: include/net/xdp.h:185
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
In kernel/bpf/devmap.c (ffffffff8126c8ab)
Location: include/net/xdp.h:186
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126e4ce)
Location: include/net/xdp.h:186
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8190ece6)
Location: include/net/xdp.h:186
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8191eb5b)
Location: include/net/xdp.h:186
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
In kernel/bpf/devmap.c (ffffffff812baae8)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc12f)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81a62492)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81a73dc1)
Location: include/net/xdp.h:260
Inline: True
```
```
In net/core/filter.c (ffffffff81c4be98)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
```
```
In net/bpf/test_run.c (ffffffff81cb386a)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In kernel/bpf/devmap.c (ffffffff8131ded4)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f522)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81becc32)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81c07e82)
Location: include/net/xdp.h:260
Inline: True
```
```
In net/core/filter.c (ffffffff81e00bf8)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
```
```
In net/bpf/test_run.c (ffffffff81e71aba)
Location: include/net/xdp.h:260
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In kernel/bpf/devmap.c (ffffffff8134dcc4)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f323)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81c45132)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81c4f856)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d510)
Location: include/net/xdp.h:264
Inline: True
```
```
In net/core/filter.c (ffffffff81e72719)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
```
```
In net/bpf/test_run.c (ffffffff81ecd687)
Location: include/net/xdp.h:264
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In kernel/bpf/devmap.c (ffffffff813751d4)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376991)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81cfa381)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81d0543d)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d21e60)
Location: include/net/xdp.h:263
Inline: True
```
```
In net/core/filter.c (ffffffff81f31e0e)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
```
```
In net/bpf/test_run.c (ffffffff81f90eb7)
Location: include/net/xdp.h:263
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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

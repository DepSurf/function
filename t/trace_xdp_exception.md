# Function: <code>trace_xdp_exception</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0c2e)
Location: include/trace/events/xdp.h:25
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_receive_skb_internal
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
In drivers/net/tun.c (ffffffff816ffa05)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff8184a7c6)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:generic_xdp_tx
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
In drivers/net/tun.c (ffffffff8173d1cb)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff8189484a)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
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
In drivers/net/tun.c (ffffffff81760997)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff818b5257)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
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
In drivers/net/tun.c (ffffffff8179e183)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81901c44)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffff817c1c13)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81933e84)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff81226f34)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8188cb44)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffff81a08846)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff8122da99)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8189adb7)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff818a89e3)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81a09e06)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff81232b69)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8187d617)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8188bb51)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff819f0796)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff8126cc97)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d1ec)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In drivers/net/tun.c (ffffffff8190ec97)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8191eaaa)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81aa1f86)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
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
In kernel/bpf/devmap.c (ffffffff812bb99b)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc30e)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In drivers/net/tun.c (ffffffff81a6242e)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81a73d14)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81c1a2df)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff8131ed34)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f706)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In drivers/net/tun.c (ffffffff81becbce)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81c07e4d)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81dcb37f)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff8134eb54)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f52e)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In drivers/net/tun.c (ffffffff81c450ce)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81c4f80c)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d648)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81e3e11b)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/devmap.c (ffffffff81376051)
Location: include/trace/events/xdp.h:29
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376b9e)
Location: include/trace/events/xdp.h:29
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In drivers/net/tun.c (ffffffff81cfa317)
Location: include/trace/events/xdp.h:29
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81d055be)
Location: include/trace/events/xdp.h:29
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d21f98)
Location: include/trace/events/xdp.h:29
Inline: True
```
```
In net/core/dev.c (ffffffff81efc9bb)
Location: include/trace/events/xdp.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffff8000109dd0b0)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffff800010bd2168)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (c0ac3034)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2d44)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In net/core/dev.c (c0cecd38)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (c000000000a9e71c)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (c000000000cb06a0)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffe000627608)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/dev.c (ffffffe00075c6dc)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffff817866e3)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff818d3e84)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffff81766033)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff8188dd14)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffff817b6a93)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81924e84)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
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
In drivers/net/tun.c (ffffffff817d0ca3)
Location: include/trace/events/xdp.h:28
Inline: True
```
```
In net/core/dev.c (ffffffff81946329)
Location: include/trace/events/xdp.h:28
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
</ul>

## Differences

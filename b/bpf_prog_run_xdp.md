# Function: <code>bpf_prog_run_xdp</code>

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
In net/core/dev.c (ffffffff817d0a4f)
Location: include/linux/filter.h:560
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff816ff901)
Location: include/linux/filter.h:565
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff8184a69a)
Location: include/linux/filter.h:565
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
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
In drivers/net/tun.c (ffffffff8173d0a5)
Location: include/linux/filter.h:605
Inline: True
```
```
In net/core/dev.c (ffffffff818949ec)
Location: include/linux/filter.h:605
Inline: True
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
In drivers/net/tun.c (ffffffff81763624)
Location: include/linux/filter.h:640
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff818b546f)
Location: include/linux/filter.h:640
Inline: True
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
In drivers/net/tun.c (ffffffff817a1351)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff818fabbe)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff817c6311)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff8192cce2)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In kernel/bpf/devmap.c (ffffffff81226f05)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8188ce36)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In net/core/dev.c (ffffffff81a0671e)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81a7e278)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff8122da65)
Location: include/linux/filter.h:734
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In kernel/bpf/cpumap.c (ffffffff8122ed65)
Location: include/linux/filter.h:734
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8189b09e)
Location: include/linux/filter.h:734
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff818a8963)
Location: include/linux/filter.h:734
Inline: True
```
```
In net/core/dev.c (ffffffff81a07cd2)
Location: include/linux/filter.h:734
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81a878da)
Location: include/linux/filter.h:734
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff81232b35)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In kernel/bpf/cpumap.c (ffffffff81233c75)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8187d905)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8188bac4)
Location: include/linux/filter.h:777
Inline: True
```
```
In net/core/dev.c (ffffffff819ea667)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81a70d63)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff8126bc76)
Location: include/linux/filter.h:793
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d7f8)
Location: include/linux/filter.h:793
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8190ef75)
Location: include/linux/filter.h:793
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191ea14)
Location: include/linux/filter.h:793
Inline: True
```
```
In net/core/dev.c (ffffffff81aa1c6a)
Location: include/linux/filter.h:793
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81b2a649)
Location: include/linux/filter.h:793
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff812baab7)
Location: include/linux/filter.h:796
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bbff8)
Location: include/linux/filter.h:796
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81a639b6)
Location: include/linux/filter.h:796
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81a73c6c)
Location: include/linux/filter.h:796
Inline: True
```
```
In net/core/dev.c (ffffffff81c19e4a)
Location: include/linux/filter.h:796
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81cb429d)
Location: include/linux/filter.h:796
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff8131dea3)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f3e4)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81bf2b96)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81c07d9c)
Location: include/linux/filter.h:768
Inline: True
```
```
In net/core/dev.c (ffffffff81dcaeca)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81e7250d)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff8134dc93)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f234)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81c49dca)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c4f6fc)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d4bc)
Location: include/linux/filter.h:768
Inline: True
```
```
In net/core/dev.c (ffffffff81e3ba53)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81ece684)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/bpf/devmap.c (ffffffff813751a3)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff813768a6)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81cff75a)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d053ec)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d21e0c)
Location: include/net/xdp.h:507
Inline: True
```
```
In net/core/dev.c (ffffffff81ef9f93)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81f91ebb)
Location: include/net/xdp.h:507
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In drivers/net/tun.c (ffff8000109e1430)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffff800010bcf5d4)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (c0ac65c0)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2ce0)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In net/core/dev.c (c0ce59a0)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (c000000000aa311c)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (c000000000ca6404)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffe00062af90)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffe000755aea)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff8178adf1)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff818ccce2)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff8176a741)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff81886d72)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff817bb191)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff8191dce2)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff817d41c7)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In net/core/dev.c (ffffffff8193f352)
Location: include/linux/filter.h:696
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
</ul>

## Differences

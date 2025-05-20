# Function: <code>netif_is_bond_slave</code>

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
In net/core/link_watch.c (ffffffff818ae297)
Location: include/linux/netdevice.h:4308
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
In net/core/link_watch.c (ffffffff818d2517)
Location: include/linux/netdevice.h:4545
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
In net/core/link_watch.c (ffffffff8191f7b9)
Location: include/linux/netdevice.h:4571
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
In net/core/link_watch.c (ffffffff819519f9)
Location: include/linux/netdevice.h:4584
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
In net/core/link_watch.c (ffffffff81a22865)
Location: include/linux/netdevice.h:4777
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
In net/core/link_watch.c (ffffffff81a22bc5)
Location: include/linux/netdevice.h:4973
Inline: True
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
In net/core/link_watch.c (ffffffff81a09ef5)
Location: include/linux/netdevice.h:5104
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
In kernel/bpf/devmap.c (ffffffff8126bd6b)
Location: include/linux/netdevice.h:5152
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d899)
Location: include/linux/netdevice.h:5152
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff8190f052)
Location: include/linux/netdevice.h:5152
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191eab7)
Location: include/linux/netdevice.h:5152
Inline: True
```
```
In net/core/dev.c (ffffffff81aa1e28)
Location: include/linux/netdevice.h:5152
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/link_watch.c (ffffffff81abc3f5)
Location: include/linux/netdevice.h:5152
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81b2a6ad)
Location: include/linux/netdevice.h:5152
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
In kernel/bpf/devmap.c (ffffffff812babc8)
Location: include/linux/netdevice.h:4972
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc0bb)
Location: include/linux/netdevice.h:4972
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81a63c62)
Location: include/linux/netdevice.h:4972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81a73d2c)
Location: include/linux/netdevice.h:4972
Inline: True
```
```
In net/core/dev.c (ffffffff81c19fcb)
Location: include/linux/netdevice.h:4972
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/link_watch.c (ffffffff81c36f42)
Location: include/linux/netdevice.h:4972
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb4310)
Location: include/linux/netdevice.h:4972
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
In kernel/bpf/devmap.c (ffffffff8131dfac)
Location: include/linux/netdevice.h:5016
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f4a4)
Location: include/linux/netdevice.h:5016
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81bf2e41)
Location: include/linux/netdevice.h:5016
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81c07f35)
Location: include/linux/netdevice.h:5016
Inline: True
```
```
In net/core/dev.c (ffffffff81dcb02e)
Location: include/linux/netdevice.h:5016
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/link_watch.c (ffffffff81dea572)
Location: include/linux/netdevice.h:5016
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81e72580)
Location: include/linux/netdevice.h:5016
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
In kernel/bpf/devmap.c (ffffffff8134dd9c)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f2f4)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81c4a014)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c4f81e)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d6a1)
Location: include/linux/netdevice.h:5051
Inline: True
```
```
In net/core/dev.c (ffffffff81e3bbb8)
Location: include/linux/netdevice.h:5051
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/link_watch.c (ffffffff81e5bd52)
Location: include/linux/netdevice.h:5051
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81ece721)
Location: include/linux/netdevice.h:5051
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
In kernel/bpf/devmap.c (ffffffff813752ac)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376966)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In drivers/net/tun.c (ffffffff81cff9a4)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d055c9)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d21ff1)
Location: include/linux/netdevice.h:5127
Inline: True
```
```
In net/core/dev.c (ffffffff81efa0f8)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/link_watch.c (ffffffff81f1b10e)
Location: include/linux/netdevice.h:5127
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81f91f52)
Location: include/linux/netdevice.h:5127
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/link_watch.c (ffff800010bf3584)
Location: include/linux/netdevice.h:4584
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
In net/core/link_watch.c (c0d0bf48)
Location: include/linux/netdevice.h:4584
Inline: True
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
In net/core/link_watch.c (c000000000cd89c8)
Location: include/linux/netdevice.h:4584
Inline: True
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
In net/core/link_watch.c (ffffffe000774f92)
Location: include/linux/netdevice.h:4584
Inline: True
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
In net/core/link_watch.c (ffffffff818f19c9)
Location: include/linux/netdevice.h:4584
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
In net/core/link_watch.c (ffffffff818ab809)
Location: include/linux/netdevice.h:4584
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
In net/core/link_watch.c (ffffffff819429f9)
Location: include/linux/netdevice.h:4584
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
In net/core/link_watch.c (ffffffff819642f9)
Location: include/linux/netdevice.h:4584
Inline: True
```
</details>
</li>
</ul>

## Differences

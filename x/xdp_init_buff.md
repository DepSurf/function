# Function: <code>xdp_init_buff</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187d8d6)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8188ba79)
Location: include/net/xdp.h:80
Inline: True
```
```
In net/core/dev.c (ffffffff819ea5fc)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81a71cf8)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/tun.c (ffffffff8190ef46)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191e9c9)
Location: include/net/xdp.h:80
Inline: True
```
```
In net/core/dev.c (ffffffff81aa1c03)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81b2b44f)
Location: include/net/xdp.h:80
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/tun.c (ffffffff81a63998)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81a73c28)
Location: include/net/xdp.h:114
Inline: True
```
```
In net/core/dev.c (ffffffff81c19de1)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81cb5757)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/tun.c (ffffffff81bf2b78)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/xen-netfront.c (ffffffff81c07d58)
Location: include/net/xdp.h:114
Inline: True
```
```
In net/core/dev.c (ffffffff81dcae61)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81e73c27)
Location: include/net/xdp.h:114
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/tun.c (ffffffff81c49da9)
Location: include/net/xdp.h:118
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c549d8)
Location: include/net/xdp.h:118
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d478)
Location: include/net/xdp.h:118
Inline: True
```
```
In net/core/dev.c (ffffffff81e3b9e3)
Location: include/net/xdp.h:118
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81ecf996)
Location: include/net/xdp.h:118
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/tun.c (ffffffff81cff739)
Location: include/net/xdp.h:117
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d0b098)
Location: include/net/xdp.h:117
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In drivers/net/xen-netfront.c (ffffffff81d21dc8)
Location: include/net/xdp.h:117
Inline: True
```
```
In net/core/dev.c (ffffffff81ef9f23)
Location: include/net/xdp.h:117
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81f932e6)
Location: include/net/xdp.h:117
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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

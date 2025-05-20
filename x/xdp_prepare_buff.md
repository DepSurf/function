# Function: <code>xdp_prepare_buff</code>

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
In drivers/net/tun.c (ffffffff8187d8fd)
Location: include/net/xdp.h:87
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8188baa5)
Location: include/net/xdp.h:87
Inline: True
```
```
In net/core/dev.c (ffffffff819ea62e)
Location: include/net/xdp.h:87
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81a71cfc)
Location: include/net/xdp.h:87
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
In drivers/net/tun.c (ffffffff8190ef6d)
Location: include/net/xdp.h:87
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191e9f5)
Location: include/net/xdp.h:87
Inline: True
```
```
In net/core/dev.c (ffffffff81aa1c31)
Location: include/net/xdp.h:87
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81b2b453)
Location: include/net/xdp.h:87
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
In drivers/net/tun.c (ffffffff81a6647c)
Location: include/net/xdp.h:122
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a73c4d)
Location: include/net/xdp.h:122
Inline: True
```
```
In net/core/dev.c (ffffffff81c19e11)
Location: include/net/xdp.h:122
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81cb5774)
Location: include/net/xdp.h:122
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
In drivers/net/tun.c (ffffffff81bf191c)
Location: include/net/xdp.h:122
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c07d7d)
Location: include/net/xdp.h:122
Inline: True
```
```
In net/core/dev.c (ffffffff81dcae91)
Location: include/net/xdp.h:122
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81e73c44)
Location: include/net/xdp.h:122
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
In drivers/net/tun.c (ffffffff81c4a5ac)
Location: include/net/xdp.h:126
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c54a0e)
Location: include/net/xdp.h:126
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d49d)
Location: include/net/xdp.h:126
Inline: True
```
```
In net/core/dev.c (ffffffff81e3ba1a)
Location: include/net/xdp.h:126
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81ecf9b3)
Location: include/net/xdp.h:126
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
In drivers/net/tun.c (ffffffff81cfff2b)
Location: include/net/xdp.h:125
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d0b0ce)
Location: include/net/xdp.h:125
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In drivers/net/xen-netfront.c (ffffffff81d21ded)
Location: include/net/xdp.h:125
Inline: True
```
```
In net/core/dev.c (ffffffff81ef9f5a)
Location: include/net/xdp.h:125
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/bpf/test_run.c (ffffffff81f93303)
Location: include/net/xdp.h:125
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

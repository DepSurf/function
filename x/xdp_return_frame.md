# Function: <code>xdp_return_frame</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818baba0)
Location: net/core/xdp.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff818baba0-ffffffff818babbb: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1b10)
Location: net/core/xdp.c:364
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff818e1b10-ffffffff818e1b2b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930590)
Location: net/core/xdp.c:436
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81930590-ffffffff819305ab: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819626f0)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff819626f0-ffffffff8196270b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35ee0)
Location: net/core/xdp.c:371
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81a35ee0-ffffffff81a35ef9: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37dc0)
Location: net/core/xdp.c:375
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81a37dc0-ffffffff81a37ddb: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ef60)
Location: net/core/xdp.c:376
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81a1ef60-ffffffff81a1ef7b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3000)
Location: net/core/xdp.c:377
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81ad3000-ffffffff81ad301b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51b10)
Location: net/core/xdp.c:410
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81c51b10-ffffffff81c51bba: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e06ed0)
Location: net/core/xdp.c:408
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81e06ed0-ffffffff81e06f76: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e79810)
Location: net/core/xdp.c:410
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
**Symbols:**

```
ffffffff81e79810-ffffffff81e798d1: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39930)
Location: net/core/xdp.c:410
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_ptr_free
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
**Symbols:**

```
ffffffff81f39930-ffffffff81f399f1: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06fc8)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffff800010c06fc8-ffff800010c07000: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d201e0)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
```
**Symbols:**

```
c0d201e0-c0d2020c: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1870)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
c000000000cf1870-c000000000cf1898: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe0007853c2)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffe0007853c2-ffffffe0007853f4: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819026c0)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff819026c0-ffffffff819026db: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc4f0)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff818bc4f0-ffffffff818bc50b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819536f0)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff819536f0-ffffffff8195370b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_return_frame(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975210)
Location: net/core/xdp.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81975210-ffffffff8197522b: xdp_return_frame (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

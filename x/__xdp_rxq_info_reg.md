# Function: <code>__xdp_rxq_info_reg</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id, u32 frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51680)
Location: net/core/xdp.c:165
Inline: False
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81c51680-ffffffff81c5179f: __xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id, u32 frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e067e0)
Location: net/core/xdp.c:165
Inline: False
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e067e0-ffffffff81e068ff: __xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id, u32 frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e79140)
Location: net/core/xdp.c:167
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_open
  - net/core/dev.c:alloc_netdev_mqs
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e79140-ffffffff81e79266: __xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id, u32 frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39010)
Location: net/core/xdp.c:167
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_open
  - net/core/dev.c:alloc_netdev_mqs
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f39010-ffffffff81f39136: __xdp_rxq_info_reg (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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

# Function: <code>netif_napi_add_weight</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void netif_napi_add_weight(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6361
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81f02757-ffffffff81f02797: netif_napi_add_weight.cold (STB_LOCAL)
ffffffff81c11bb0-ffffffff81c11e89: netif_napi_add_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void netif_napi_add_weight(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6350
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff820ab44b-ffffffff820ab460: netif_napi_add_weight.cold (STB_LOCAL)
ffffffff81dc37b0-ffffffff81dc3a9f: netif_napi_add_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void netif_napi_add_weight(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6330
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff8212ca80-ffffffff8212ca95: netif_napi_add_weight.cold (STB_LOCAL)
ffffffff81e32c50-ffffffff81e32f3f: netif_napi_add_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void netif_napi_add_weight(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6445
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff8220e7e9-ffffffff8220e7fe: netif_napi_add_weight.cold (STB_LOCAL)
ffffffff81ef1bc0-ffffffff81ef1ea8: netif_napi_add_weight (STB_GLOBAL)
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

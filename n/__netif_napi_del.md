# Function: <code>__netif_napi_del</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a061b0)
Location: net/core/dev.c:6785
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81a061b0-ffffffff81a06298: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ecce0)
Location: net/core/dev.c:6975
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff819ecce0-ffffffff819ecde4: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9de50)
Location: net/core/dev.c:6965
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81a9de50-ffffffff81a9dfed: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0efc0)
Location: net/core/dev.c:6460
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81c0efc0-ffffffff81c0f186: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbed00)
Location: net/core/dev.c:6446
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81dbed00-ffffffff81dbeec6: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2e8d0)
Location: net/core/dev.c:6427
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81e2e8d0-ffffffff81e2ea9a: __netif_napi_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __netif_napi_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eed250)
Location: net/core/dev.c:6543
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/dev.c:free_netdev
```
**Symbols:**

```
ffffffff81eed250-ffffffff81eed41a: __netif_napi_del (STB_GLOBAL)
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

# Function: <code>napi_by_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct napi_struct *napi_by_id(unsigned int napi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817138d0)
Location: net/core/dev.c:4672
Inline: True
Direct callers:
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff817138d0-ffffffff8171390f: napi_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783382)
Location: net/core/dev.c:4953
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab7b9)
Location: net/core/dev.c:5035
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:sk_busy_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9e0d)
Location: net/core/dev.c:5254
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184372d)
Location: net/core/dev.c:5395
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8189185d)
Location: net/core/dev.c:5525
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff818b23de)
Location: net/core/dev.c:6078
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff818fede9)
Location: net/core/dev.c:6088
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff81931158)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff81a0533c)
Location: net/core/dev.c:6404
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff81a06a28)
Location: net/core/dev.c:6506
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff819edd09)
Location: net/core/dev.c:6627
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9ef74)
Location: net/core/dev.c:6613
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11d65)
Location: net/core/dev.c:6099
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc395d)
Location: net/core/dev.c:6088
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e32dfd)
Location: net/core/dev.c:6065
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct napi_struct *napi_by_id(unsigned int napi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1d81)
Location: net/core/dev.c:6147
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
Direct callers:
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
```
**Symbols:**

```
ffffffff81efd050-ffffffff81efd093: napi_by_id (STB_GLOBAL)
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
In net/core/dev.c (ffff800010bce954)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (c0ce55f0)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (c000000000ca5f10)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffe000758c70)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff818d1158)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff8188b008)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff81922158)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
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
In net/core/dev.c (ffffffff81940078)
Location: net/core/dev.c:6014
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:dev_get_by_napi_id
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

# Function: <code>__skb_udp_tunnel_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8178ae03)
Location: net/ipv4/udp_offload.c:28
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff817f86a3)
Location: net/ipv4/udp_offload.c:17
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff81829553)
Location: net/ipv4/udp_offload.c:17
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff8184a529)
Location: net/ipv4/udp_offload.c:17
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff818ca1c9)
Location: net/ipv4/udp_offload.c:17
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff81920549)
Location: net/ipv4/udp_offload.c:17
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff8194f38b)
Location: net/ipv4/udp_offload.c:18
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff819b3ba8)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff819ea8d8)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad84d0)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81ad84d0-ffffffff81ad89b0: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae4970)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81ae4970-ffffffff81ae4ea5: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81acfbc0)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81acfbc0-ffffffff81ad00cd: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8e5e0)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81b8e5e0-ffffffff81b8eaed: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d1fd80)
Location: net/ipv4/udp_offload.c:15
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81d1fd80-ffffffff81d202bd: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee6f80)
Location: net/ipv4/udp_offload.c:15
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81ee6f80-ffffffff81ee74ba: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f46820)
Location: net/ipv4/udp_offload.c:16
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff81f46820-ffffffff81f46d5c: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200c960)
Location: net/ipv4/udp_offload.c:16
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffff8200c960-ffffffff8200ce9c: __skb_udp_tunnel_segment (STB_LOCAL)
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
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffff800010ca0470)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffff800010ca0470-ffff800010ca08d4: __skb_udp_tunnel_segment (STB_LOCAL)
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
In net/ipv4/udp_offload.c (c0dad6cc)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c000000000db2bc0)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
c000000000db2bc0-c000000000db31e0: __skb_udp_tunnel_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_udp_tunnel_segment(struct sk_buff *skb, netdev_features_t features, struct sk_buff * (*gso_inner_segment)(struct sk_buff *, netdev_features_t), __be16 new_protocol, bool is_ipv6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffe0007fcb0e)
Location: net/ipv4/udp_offload.c:14
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
**Symbols:**

```
ffffffe0007fcb0e-ffffffe0007fcfa8: __skb_udp_tunnel_segment (STB_LOCAL)
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
In net/ipv4/udp_offload.c (ffffffff8198a748)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff81944208)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff819f4f18)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
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
In net/ipv4/udp_offload.c (ffffffff819ff112)
Location: net/ipv4/udp_offload.c:14
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>

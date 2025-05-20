# Function: <code>dev_direct_xmit</code>

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
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818939b0)
Location: net/core/dev.c:3612
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff818939b0-ffffffff81893b74: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b43d0)
Location: net/core/dev.c:3907
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff818b43d0-ffffffff818b458a: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900cf0)
Location: net/core/dev.c:3916
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81900cf0-ffffffff81900eb1: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81933020)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81933020-ffffffff819331e1: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07e50)
Location: net/core/dev.c:4174
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81a07e50-ffffffff81a08051: dev_direct_xmit (STB_GLOBAL)
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
In net/packet/af_packet.c (ffffffff81b95197)
Location: include/linux/netdevice.h:2887
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/selftests.c (ffffffff81a366f7)
Location: include/linux/netdevice.h:2954
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff81b841d1)
Location: include/linux/netdevice.h:2954
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/selftests.c (ffffffff81aec3d7)
Location: include/linux/netdevice.h:2974
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff81c502c1)
Location: include/linux/netdevice.h:2974
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/selftests.c (ffffffff81c6ed80)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff81df17e5)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/selftests.c (ffffffff81e26ad0)
Location: include/linux/netdevice.h:3042
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff81fc5795)
Location: include/linux/netdevice.h:3042
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/selftests.c (ffffffff81e9c070)
Location: include/linux/netdevice.h:3097
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff82027771)
Location: include/linux/netdevice.h:3097
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_xmit
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
In net/core/selftests.c (ffffffff81f5e7ff)
Location: include/linux/netdevice.h:3178
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/packet/af_packet.c (ffffffff820f6fc4)
Location: include/linux/netdevice.h:3178
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_xmit
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
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd1020)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffff800010bd1020-ffff800010bd1240: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cebc80)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c0cebc80-c0cebe6c: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf260)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c000000000caf260-c000000000caf4bc: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b61a)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffe00075b61a-ffffffe00075b7be: dev_direct_xmit (STB_GLOBAL)
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
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d3020)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff818d3020-ffffffff818d31e1: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ceb0)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff8188ceb0-ffffffff8188d071: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81924020)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81924020-ffffffff819241e1: dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81945490)
Location: net/core/dev.c:3816
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81945490-ffffffff8194564b: dev_direct_xmit (STB_GLOBAL)
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

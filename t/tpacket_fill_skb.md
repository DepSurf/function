# Function: <code>tpacket_fill_skb</code>

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
In net/packet/af_packet.c (ffffffff818073c5)
Location: net/packet/af_packet.c:2350
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81878c49)
Location: net/packet/af_packet.c:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff818ad1c9)
Location: net/packet/af_packet.c:2423
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff818d2acc)
Location: net/packet/af_packet.c:2480
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff819579fa)
Location: net/packet/af_packet.c:2469
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff819af6a7)
Location: net/packet/af_packet.c:2443
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff819e6be0)
Location: net/packet/af_packet.c:2445
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81a56113)
Location: net/packet/af_packet.c:2452
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81a8d5f3)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2482
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81b87bb0-ffffffff81b8806c: tpacket_fill_skb (STB_LOCAL)
ffffffff81b8c212-ffffffff81b8c22d: tpacket_fill_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2499
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81b97690-ffffffff81b97b4c: tpacket_fill_skb (STB_LOCAL)
ffffffff81c33203-ffffffff81c3321e: tpacket_fill_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2508
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81b86690-ffffffff81b86b47: tpacket_fill_skb (STB_LOCAL)
ffffffff81c25505-ffffffff81c25520: tpacket_fill_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2514
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81c52a50-ffffffff81c52f03: tpacket_fill_skb (STB_LOCAL)
ffffffff81d4195a-ffffffff81d41975: tpacket_fill_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2565
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81df66a0-ffffffff81df6be7: tpacket_fill_skb (STB_LOCAL)
ffffffff81f0e339-ffffffff81f0e354: tpacket_fill_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fcac60)
Location: net/packet/af_packet.c:2565
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81fcac60-ffffffff81fcb1e9: tpacket_fill_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff8202bee0)
Location: net/packet/af_packet.c:2577
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8202bee0-ffffffff8202c4cb: tpacket_fill_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpacket_fill_skb(struct packet_sock *po, struct sk_buff *skb, void *frame, struct net_device *dev, void *data, int tp_len, __be16 proto, unsigned char *addr, int hlen, int copylen, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820fb990)
Location: net/packet/af_packet.c:2571
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff820fb990-ffffffff820fbf6f: tpacket_fill_skb (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d59130)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (c0e5ab24)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (c000000000e94ce8)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffe000891434)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81a2cc83)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff819e9e73)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81a98833)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/packet/af_packet.c (ffffffff81aa4ecd)
Location: net/packet/af_packet.c:2471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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

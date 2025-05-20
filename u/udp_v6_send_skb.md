# Function: <code>udp_v6_send_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e1b00)
Location: net/ipv6/udp.c:1029
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff817e1b00-ffffffff817e1e27: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8184ff70)
Location: net/ipv6/udp.c:935
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff8184ff70-ffffffff81850297: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81881d70)
Location: net/ipv6/udp.c:921
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81881d70-ffffffff81882097: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a8550)
Location: net/ipv6/udp.c:1032
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff818a8550-ffffffff818a88a0: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192b000)
Location: net/ipv6/udp.c:1037
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8192b000-ffffffff8192b350: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff819832e0)
Location: net/ipv6/udp.c:1033
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819832e0-ffffffff81983702: udp_v6_send_skb.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff819b97f0)
Location: net/ipv6/udp.c:1113
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819b97f0-ffffffff819b9c12: udp_v6_send_skb.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a28420)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a28420-ffffffff81a2885a: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a5eeb0)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a5eeb0-ffffffff81a5f343: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b57800)
Location: net/ipv6/udp.c:1107
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b57800-ffffffff81b57b77: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b65d10)
Location: net/ipv6/udp.c:1164
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b65d10-ffffffff81b66087: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b53db0)
Location: net/ipv6/udp.c:1177
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b53db0-ffffffff81b5420d: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: net/ipv6/udp.c:1179
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81c1d260-ffffffff81c1d6bb: udp_v6_send_skb (STB_LOCAL)
ffffffff81d40702-ffffffff81d40728: udp_v6_send_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: net/ipv6/udp.c:1188
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81db98c0-ffffffff81db9d10: udp_v6_send_skb (STB_LOCAL)
ffffffff81f0d0dc-ffffffff81f0d102: udp_v6_send_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: net/ipv6/udp.c:1223
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81f89950-ffffffff81f89da0: udp_v6_send_skb (STB_LOCAL)
ffffffff820b4526-ffffffff820b454c: udp_v6_send_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: net/ipv6/udp.c:1240
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81fe9200-ffffffff81fe9656: udp_v6_send_skb (STB_LOCAL)
ffffffff82135606-ffffffff82135625: udp_v6_send_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b5d10)
Location: net/ipv6/udp.c:1214
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff820b5d10-ffffffff820b6144: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffff800010d24d28)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffff800010d24d28-ffff800010d25180: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff *skb, struct flowi6 *fl6, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e28288)
Location: net/ipv6/udp.c:1102
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
c0e28288-c0e286dc: udp_v6_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (c000000000e54480)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
c000000000e54480-c000000000e549f4: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffe00086558a)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffe00086558a-ffffffe0008659a4: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff819fe540)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819fe540-ffffffff819fe9d3: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bb300)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819bb300-ffffffff819bb793: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a68fc0)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a68fc0-ffffffff81a69453: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a755a0)
Location: net/ipv6/udp.c:1102
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a755a0-ffffffff81a75a33: udp_v6_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>

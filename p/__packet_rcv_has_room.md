# Function: <code>__packet_rcv_has_room</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81804220)
Location: net/packet/af_packet.c:1265
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_rcv_has_room
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81804220-ffffffff818042ff: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875240)
Location: net/packet/af_packet.c:1265
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff81875240-ffffffff8187531e: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a9710)
Location: net/packet/af_packet.c:1264
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff818a9710-ffffffff818a97ee: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d0430)
Location: net/packet/af_packet.c:1271
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff818d0430-ffffffff818d0502: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81955350)
Location: net/packet/af_packet.c:1259
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff81955350-ffffffff81955422: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819adf70)
Location: net/packet/af_packet.c:1235
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff819adf70-ffffffff819ae095: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(struct packet_sock *po, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e4900)
Location: net/packet/af_packet.c:1236
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_rcv_has_room
```
**Symbols:**

```
ffffffff819e4900-ffffffff819e4a25: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a53a00)
Location: net/packet/af_packet.c:1227
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81a53a00-ffffffff81a53b4d: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8a5f0)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81a8a5f0-ffffffff81a8a73d: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b86160)
Location: net/packet/af_packet.c:1231
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81b86160-ffffffff81b862dc: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b95a80)
Location: net/packet/af_packet.c:1235
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81b95a80-ffffffff81b95bfc: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b84950)
Location: net/packet/af_packet.c:1236
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81b84950-ffffffff81b84aca: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50df0)
Location: net/packet/af_packet.c:1237
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81c50df0-ffffffff81c50f6a: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df2290)
Location: net/packet/af_packet.c:1273
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81df2290-ffffffff81df2413: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc6390)
Location: net/packet/af_packet.c:1273
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81fc6390-ffffffff81fc6513: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82026900)
Location: net/packet/af_packet.c:1275
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff82026900-ffffffff82026a83: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f6310)
Location: net/packet/af_packet.c:1275
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff820f6310-ffffffff820f6493: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d57410)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffff800010d57410-ffff800010d5755c: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e59964)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
c0e59964-c0e59aa4: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e929d0)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
c000000000e929d0-c000000000e92bbc: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088f25c)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffe00088f25c-ffffffe00088f38a: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a29c80)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81a29c80-ffffffff81a29dcd: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e6e70)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff819e6e70-ffffffff819e6fbd: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a95830)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81a95830-ffffffff81a9597d: __packet_rcv_has_room (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __packet_rcv_has_room(const struct packet_sock *po, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa2470)
Location: net/packet/af_packet.c:1228
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81aa2470-ffffffff81aa25bd: __packet_rcv_has_room (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct packet_sock *po</code> ➡️ <code>const struct packet_sock *po</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
</li>
</ul>
</details>
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

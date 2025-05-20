# Function: <code>prb_dispatch_next_block</code>

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
In net/packet/af_packet.c (ffffffff818030be)
Location: net/packet/af_packet.c:916
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff818776e8)
Location: net/packet/af_packet.c:916
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff818aaef8)
Location: net/packet/af_packet.c:915
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff818d41e8)
Location: net/packet/af_packet.c:923
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81958c3b)
Location: net/packet/af_packet.c:911
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819ae7d0)
Location: net/packet/af_packet.c:887
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819ae7d0-ffffffff819ae80d: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e53b0)
Location: net/packet/af_packet.c:888
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819e53b0-ffffffff819e53ed: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a53130)
Location: net/packet/af_packet.c:880
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a53130-ffffffff81a5316e: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a89d20)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a89d20-ffffffff81a89d5e: prb_dispatch_next_block (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81b8691c)
Location: net/packet/af_packet.c:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81b9624c)
Location: net/packet/af_packet.c:886
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81b87db8)
Location: net/packet/af_packet.c:887
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81c56d86)
Location: net/packet/af_packet.c:888
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81df615b)
Location: net/packet/af_packet.c:924
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff81fca6ab)
Location: net/packet/af_packet.c:924
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In net/packet/af_packet.c (ffffffff8202b031)
Location: net/packet/af_packet.c:926
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820fab38)
Location: net/packet/af_packet.c:926
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d56b98)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffff800010d56b98-ffff800010d56c08: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e57488)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
c0e57488-c0e574e8: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e90140)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
c000000000e90140-c000000000e901d4: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088e536)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffe00088e536-ffffffe00088e59c: prb_dispatch_next_block (STB_LOCAL)
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
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a293b0)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a293b0-ffffffff81a293ee: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e65a0)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819e65a0-ffffffff819e65de: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a94f60)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a94f60-ffffffff81a94f9e: prb_dispatch_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *prb_dispatch_next_block(struct tpacket_kbdq_core *pkc, struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa1230)
Location: net/packet/af_packet.c:881
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81aa1230-ffffffff81aa126e: prb_dispatch_next_block (STB_LOCAL)
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

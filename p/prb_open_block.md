# Function: <code>prb_open_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81802e00)
Location: net/packet/af_packet.c:841
Inline: False
Direct callers:
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81802e00-ffffffff81802eeb: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81874190)
Location: net/packet/af_packet.c:841
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81874190-ffffffff8187427b: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a8780)
Location: net/packet/af_packet.c:840
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff818a8780-ffffffff818a886b: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cefd0)
Location: net/packet/af_packet.c:848
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff818cefd0-ffffffff818cf0bb: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81953f60)
Location: net/packet/af_packet.c:836
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81953f60-ffffffff8195404b: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819ae6e0)
Location: net/packet/af_packet.c:812
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819ae6e0-ffffffff819ae7cd: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e52c0)
Location: net/packet/af_packet.c:813
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819e52c0-ffffffff819e53ad: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a53040)
Location: net/packet/af_packet.c:805
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a53040-ffffffff81a5312f: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a89c30)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a89c30-ffffffff81a89d1f: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85e70)
Location: net/packet/af_packet.c:807
Inline: False
Direct callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff81b85e70-ffffffff81b85f59: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b95780)
Location: net/packet/af_packet.c:811
Inline: False
Direct callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff81b95780-ffffffff81b95869: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b84860)
Location: net/packet/af_packet.c:812
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81b84860-ffffffff81b84949: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50d00)
Location: net/packet/af_packet.c:813
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81c50d00-ffffffff81c50de9: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df2060)
Location: net/packet/af_packet.c:849
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81df2060-ffffffff81df2165: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc6140)
Location: net/packet/af_packet.c:849
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81fc6140-ffffffff81fc6245: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820266b0)
Location: net/packet/af_packet.c:851
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff820266b0-ffffffff820267b5: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f60c0)
Location: net/packet/af_packet.c:851
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff820f60c0-ffffffff820f61c5: prb_open_block (STB_LOCAL)
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
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d56a88)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffff800010d56a88-ffff800010d56b94: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e57364)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
c0e57364-c0e57488: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e90000)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
c000000000e90000-c000000000e90140: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088e46a)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffe00088e46a-ffffffe00088e536: prb_open_block (STB_LOCAL)
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
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a292c0)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a292c0-ffffffff81a293af: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e64b0)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff819e64b0-ffffffff819e659f: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a94e70)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81a94e70-ffffffff81a94f5f: prb_open_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prb_open_block(struct tpacket_kbdq_core *pkc1, struct tpacket_block_desc *pbd1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa1140)
Location: net/packet/af_packet.c:806
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_dispatch_next_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
**Symbols:**

```
ffffffff81aa1140-ffffffff81aa122f: prb_open_block (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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

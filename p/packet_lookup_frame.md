# Function: <code>packet_lookup_frame</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81804170)
Location: net/packet/af_packet.c:491
Inline: True
Direct callers:
  - net/packet/af_packet.c:__tpacket_has_room
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81804170-ffffffff818041b3: packet_lookup_frame.isra.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875190)
Location: net/packet/af_packet.c:492
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__tpacket_has_room
```
**Symbols:**

```
ffffffff81875190-ffffffff818751d1: packet_lookup_frame.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a9660)
Location: net/packet/af_packet.c:491
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__tpacket_has_room
```
**Symbols:**

```
ffffffff818a9660-ffffffff818a96a1: packet_lookup_frame.isra.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d0370)
Location: net/packet/af_packet.c:499
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__tpacket_has_room
```
**Symbols:**

```
ffffffff818d0370-ffffffff818d03cb: packet_lookup_frame.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81955290)
Location: net/packet/af_packet.c:494
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__tpacket_has_room
```
**Symbols:**

```
ffffffff81955290-ffffffff819552ed: packet_lookup_frame.isra.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *packet_lookup_frame(struct packet_sock *po, struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819adf10)
Location: net/packet/af_packet.c:470
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819adf10-ffffffff819adf66: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *packet_lookup_frame(struct packet_sock *po, struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e48a0)
Location: net/packet/af_packet.c:471
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819e48a0-ffffffff819e48f6: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a539a0)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a539a0-ffffffff81a539f4: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8a590)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a8a590-ffffffff81a8a5e4: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85e10)
Location: net/packet/af_packet.c:470
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81b85e10-ffffffff81b85e66: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b95720)
Location: net/packet/af_packet.c:474
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81b95720-ffffffff81b95776: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b84800)
Location: net/packet/af_packet.c:475
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81b84800-ffffffff81b84856: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50ca0)
Location: net/packet/af_packet.c:476
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81c50ca0-ffffffff81c50cf6: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df1fd0)
Location: net/packet/af_packet.c:512
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:__packet_rcv_has_room
```
**Symbols:**

```
ffffffff81df1fd0-ffffffff81df2051: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc60a0)
Location: net/packet/af_packet.c:512
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:__packet_rcv_has_room
```
**Symbols:**

```
ffffffff81fc60a0-ffffffff81fc6121: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff820265f0)
Location: net/packet/af_packet.c:514
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:__packet_rcv_has_room
```
**Symbols:**

```
ffffffff820265f0-ffffffff82026696: packet_lookup_frame.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f6000)
Location: net/packet/af_packet.c:514
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:__packet_rcv_has_room
```
**Symbols:**

```
ffffffff820f6000-ffffffff820f60a6: packet_lookup_frame.isra.0 (STB_LOCAL)
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
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d56cf8)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffff800010d56cf8-ffff800010d56d60: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e59908)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c0e59908-c0e59964: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e92920)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c000000000e92920-c000000000e929d0: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088f1ee)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffe00088f1ee-ffffffe00088f25c: packet_lookup_frame (STB_LOCAL)
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
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a29c20)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a29c20-ffffffff81a29c74: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e6e10)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819e6e10-ffffffff819e6e64: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a957d0)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a957d0-ffffffff81a95824: packet_lookup_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *packet_lookup_frame(const struct packet_sock *po, const struct packet_ring_buffer *rb, unsigned int position, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa2410)
Location: net/packet/af_packet.c:463
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81aa2410-ffffffff81aa2464: packet_lookup_frame (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct packet_sock *po</code> ➡️ <code>const struct packet_sock *po</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct packet_ring_buffer *rb</code> ➡️ <code>const struct packet_ring_buffer *rb</code>
</li>
</ul>
</details>
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

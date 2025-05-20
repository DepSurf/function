# Function: <code>prb_fill_curr_block</code>

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
In net/packet/af_packet.c (ffffffff81804c70)
Location: net/packet/af_packet.c:1023
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81804c70-ffffffff81804d30: prb_fill_curr_block.isra.57 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81875690)
Location: net/packet/af_packet.c:1023
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81875690-ffffffff81875750: prb_fill_curr_block.isra.58 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff818a9b60)
Location: net/packet/af_packet.c:1022
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff818a9b60-ffffffff818a9c20: prb_fill_curr_block.isra.62 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff818d0a20)
Location: net/packet/af_packet.c:1029
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff818d0a20-ffffffff818d0ae0: prb_fill_curr_block.isra.58 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81955950)
Location: net/packet/af_packet.c:1017
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81955950-ffffffff81955a06: prb_fill_curr_block.isra.59 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff819ade00)
Location: net/packet/af_packet.c:993
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819ade00-ffffffff819adeb6: prb_fill_curr_block.isra.58 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff819e4790)
Location: net/packet/af_packet.c:994
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819e4790-ffffffff819e4845: prb_fill_curr_block.isra.60 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81a53730)
Location: net/packet/af_packet.c:986
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a53730-ffffffff81a537e7: prb_fill_curr_block.isra.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81a8a320)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a8a320-ffffffff81a8a3d7: prb_fill_curr_block.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85be0)
Location: net/packet/af_packet.c:989
Inline: False
Direct callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
```
**Symbols:**

```
ffffffff81b85be0-ffffffff81b85c98: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b955f0)
Location: net/packet/af_packet.c:993
Inline: False
Direct callers:
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
  - net/packet/af_packet.c:__packet_lookup_frame_in_block
```
**Symbols:**

```
ffffffff81b955f0-ffffffff81b956b7: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b846e0)
Location: net/packet/af_packet.c:994
Inline: False
```
**Symbols:**

```
ffffffff81b846e0-ffffffff81b84797: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50b80)
Location: net/packet/af_packet.c:995
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81c50b80-ffffffff81c50c37: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df1dd0)
Location: net/packet/af_packet.c:1031
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81df1dd0-ffffffff81df1ea3: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc5e80)
Location: net/packet/af_packet.c:1031
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81fc5e80-ffffffff81fc5f52: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82026500)
Location: net/packet/af_packet.c:1033
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff82026500-ffffffff820265d2: prb_fill_curr_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f5f10)
Location: net/packet/af_packet.c:1033
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff820f5f10-ffffffff820f5fe2: prb_fill_curr_block (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d57f68)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffff800010d57f68-ffff800010d58094: prb_fill_curr_block.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prb_fill_curr_block(char *curr, struct tpacket_kbdq_core *pkc, struct tpacket_block_desc *pbd, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e571b8)
Location: net/packet/af_packet.c:987
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c0e571b8-c0e572a4: prb_fill_curr_block (STB_LOCAL)
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
In net/packet/af_packet.c (c000000000e90dd0)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c000000000e90dd0-c000000000e90ef0: prb_fill_curr_block.isra.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffe000893b5c)
Location: net/packet/af_packet.c:987
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81a299b0)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a299b0-ffffffff81a29a67: prb_fill_curr_block.isra.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff819e6ba0)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819e6ba0-ffffffff819e6c57: prb_fill_curr_block.isra.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81a95560)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a95560-ffffffff81a95617: prb_fill_curr_block.isra.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81aa21a0)
Location: net/packet/af_packet.c:987
Inline: True
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81aa21a0-ffffffff81aa2257: prb_fill_curr_block.isra.0 (STB_LOCAL)
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

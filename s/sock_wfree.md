# Function: <code>sock_wfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81704190)
Location: net/core/sock.c:1634
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81704190-ffffffff817041e9: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176ac30)
Location: net/core/sock.c:1639
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff8176ac30-ffffffff8176ac84: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81797cf0)
Location: net/core/sock.c:1637
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81797cf0-ffffffff81797d44: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b58b0)
Location: net/core/sock.c:1780
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff817b58b0-ffffffff817b58ff: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182dd80)
Location: net/core/sock.c:1791
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff8182dd80-ffffffff8182dde1: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81878160)
Location: net/core/sock.c:1811
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81878160-ffffffff818781c4: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81898640)
Location: net/core/sock.c:1807
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81898640-ffffffff818986a4: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1939
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff818e4bd8-ffffffff818e4beb: sock_wfree.cold (STB_LOCAL)
ffffffff818e2c00-ffffffff818e2c69: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914de0)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81914de0-ffffffff81914e49: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6bd0)
Location: net/core/sock.c:2049
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff819e6bd0-ffffffff819e6c86: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6400)
Location: net/core/sock.c:2041
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff819e6400-ffffffff819e64b6: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cc070)
Location: net/core/sock.c:2070
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff819cc070-ffffffff819cc126: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b6d0)
Location: net/core/sock.c:2194
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81a7b6d0-ffffffff81a7b786: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bef590)
Location: net/core/sock.c:2349
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81bef590-ffffffff81bef791: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9c520)
Location: net/core/sock.c:2428
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81d9c520-ffffffff81d9c71d: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0ad70)
Location: net/core/sock.c:2477
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81e0ad70-ffffffff81e0af74: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec7760)
Location: net/core/sock.c:2457
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81ec7760-ffffffff81ec7964: sock_wfree (STB_GLOBAL)
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
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010badb28)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffff800010badb28-ffff800010badbc4: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb674)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
c0ccb674-c0ccb704: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c83480)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
c000000000c83480-c000000000c83578: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073fb6e)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffe00073fb6e-ffffffe00073fc02: sock_wfree (STB_GLOBAL)
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
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4de0)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff818b4de0-ffffffff818b4e49: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ed30)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff8186ed30-ffffffff8186ed99: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905de0)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81905de0-ffffffff81905e49: sock_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926e10)
Location: net/core/sock.c:1952
Inline: False
Direct callers:
  - net/unix/scm.c:unix_destruct_scm
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
**Symbols:**

```
ffffffff81926e10-ffffffff81926e79: sock_wfree (STB_GLOBAL)
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

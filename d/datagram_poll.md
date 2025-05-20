# Function: <code>datagram_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170c8d0)
Location: net/core/datagram.c:752
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_poll
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff8170c8d0-ffffffff8170c9c2: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81775320)
Location: net/core/datagram.c:774
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81775320-ffffffff81775418: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a2610)
Location: net/core/datagram.c:794
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff817a2610-ffffffff817a2708: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817c0120)
Location: net/core/datagram.c:822
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff817c0120-ffffffff817c020f: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839b30)
Location: net/core/datagram.c:836
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81839b30-ffffffff81839c25: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884270)
Location: net/core/datagram.c:834
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff81884270-ffffffff81884370: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a46f0)
Location: net/core/datagram.c:761
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff818a46f0-ffffffff818a47e2: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818efe70)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff818efe70-ffffffff818eff66: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81921e90)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff81921e90-ffffffff81921f8f: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f50d0)
Location: net/core/datagram.c:764
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff819f50d0-ffffffff819f51d5: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4b00)
Location: net/core/datagram.c:797
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff819f4b00-ffffffff819f4c05: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819dac90)
Location: net/core/datagram.c:797
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff819dac90-ffffffff819dad95: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b310)
Location: net/core/datagram.c:797
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81a8b310-ffffffff81a8b415: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c005c0)
Location: net/core/datagram.c:795
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81c005c0-ffffffff81c006d4: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81dafdc0)
Location: net/core/datagram.c:797
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81dafdc0-ffffffff81dafed4: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e20030)
Location: net/core/datagram.c:805
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81e20030-ffffffff81e2013f: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81eddf10)
Location: net/core/datagram.c:878
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/xfrm/espintcp.c:espintcp_poll
  - net/packet/af_packet.c:packet_poll
```
**Symbols:**

```
ffffffff81eddf10-ffffffff81ede01f: datagram_poll (STB_GLOBAL)
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
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc538)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffff800010bbc538-ffff800010bbc698: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8868)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
c0cd8868-c0cd8960: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c945d0)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
c000000000c945d0-c000000000c94758: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074a6ae)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffe00074a6ae-ffffffe00074a7dc: datagram_poll (STB_GLOBAL)
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
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c1e90)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff818c1e90-ffffffff818c1f8f: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187bdd0)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff8187bdd0-ffffffff8187becf: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81912e90)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff81912e90-ffffffff81912f8f: datagram_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t datagram_poll(struct file *file, struct socket *sock, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81934010)
Location: net/core/datagram.c:760
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_poll
  - net/packet/af_packet.c:packet_poll
  - net/xdp/xsk.c:xsk_poll
```
**Symbols:**

```
ffffffff81934010-ffffffff8193410f: datagram_poll (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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

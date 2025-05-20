# Function: <code>__skb_gro_checksum_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817181f0)
Location: net/core/dev.c:4483
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff817181f0-ffffffff8171829d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780380)
Location: net/core/dev.c:4764
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81780380-ffffffff8178042d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817adcd0)
Location: net/core/dev.c:4787
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff817adcd0-ffffffff817add7d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc830)
Location: net/core/dev.c:5017
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff817cc830-ffffffff817cc8dd: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81845f00)
Location: net/core/dev.c:5158
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81845f00-ffffffff81845fad: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5288
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81898ef2-ffffffff81898f16: __skb_gro_checksum_complete.cold.149 (STB_LOCAL)
ffffffff8188e450-ffffffff8188e4e0: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5837
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff818bb3a2-ffffffff818bb3b2: __skb_gro_checksum_complete.cold.157 (STB_LOCAL)
ffffffff818af400-ffffffff818af48d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5847
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81906ca9-ffffffff81906cb9: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff818fb240-ffffffff818fb2cd: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8193938e-ffffffff8193939e: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff8192d390-ffffffff8192d41d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6153
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a0ee6c-ffffffff81a0ee7c: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff81a02420-ffffffff81a024ad: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6254
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81c31160-ffffffff81c31170: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff81a02c20-ffffffff81a02cad: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6367
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81c2344d-ffffffff81c2345d: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff819e94a0-ffffffff819e9525: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a97560)
Location: net/core/dev.c:6353
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a97560-ffffffff81a975e3: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c53640)
Location: net/core/gro.c:774
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81c53640-ffffffff81c536cf: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e08ce0)
Location: net/core/gro.c:792
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81e08ce0-ffffffff81e08d6f: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7b400)
Location: net/core/gro.c:746
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81e7b400-ffffffff81e7b48f: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3b690)
Location: net/core/gro.c:746
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81f3b690-ffffffff81f3b71f: __skb_gro_checksum_complete (STB_GLOBAL)
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
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9408)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffff800010bc9408-ffff800010bc94cc: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce669c)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
c0ce669c-c0ce6748: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7000)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
c000000000ca7000-c000000000ca70fc: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007560b6)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffe0007560b6-ffffffe000756170: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff818d935e-ffffffff818d936e: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff818cd390-ffffffff818cd41d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8189319e-ffffffff818931ae: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff818874b0-ffffffff8188753d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8192a38e-ffffffff8192a39e: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff8191e390-ffffffff8191e41d: __skb_gro_checksum_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
__sum16 __skb_gro_checksum_complete(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8194ba86-ffffffff8194ba96: __skb_gro_checksum_complete.cold (STB_LOCAL)
ffffffff8193fa20-ffffffff8193faad: __skb_gro_checksum_complete (STB_GLOBAL)
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

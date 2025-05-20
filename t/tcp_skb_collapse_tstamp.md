# Function: <code>tcp_skb_collapse_tstamp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e53f0)
Location: net/ipv4/tcp_output.c:2463
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff817e53f0-ffffffff817e5451: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81815880)
Location: net/ipv4/tcp_output.c:2585
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81815880-ffffffff818158e1: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835c50)
Location: net/ipv4/tcp_output.c:2660
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81835c50-ffffffff81835ca5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5240)
Location: net/ipv4/tcp_output.c:2713
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff818b5240-ffffffff818b5295: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190a8f0)
Location: net/ipv4/tcp_output.c:2694
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff8190a8f0-ffffffff8190a945: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81938b90)
Location: net/ipv4/tcp_output.c:2725
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81938b90-ffffffff81938be5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199baf0)
Location: net/ipv4/tcp_output.c:2752
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff8199baf0-ffffffff8199bb45: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d2510)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff819d2510-ffffffff819d2565: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abf270)
Location: net/ipv4/tcp_output.c:2848
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81abf270-ffffffff81abf2c5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acac60)
Location: net/ipv4/tcp_output.c:3020
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81acac60-ffffffff81acacb5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab5c50)
Location: net/ipv4/tcp_output.c:3025
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81ab5c50-ffffffff81ab5ca5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b72ca0)
Location: net/ipv4/tcp_output.c:3025
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81b72ca0-ffffffff81b72cf5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d02380)
Location: net/ipv4/tcp_output.c:3025
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81d02380-ffffffff81d023e8: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec7550)
Location: net/ipv4/tcp_output.c:3027
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81ec7550-ffffffff81ec75b8: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f25e20)
Location: net/ipv4/tcp_output.c:3109
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81f25e20-ffffffff81f25e88: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fea7e0)
Location: net/ipv4/tcp_output.c:3167
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81fea7e0-ffffffff81fea848: tcp_skb_collapse_tstamp (STB_GLOBAL)
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
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c850d0)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffff800010c850d0-ffff800010c85160: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d943a8)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
c0d943a8-c0d94410: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d91110)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
c000000000d91110-c000000000d9117c: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e6a2a)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffe0007e6a2a-ffffffe0007e6a98: tcp_skb_collapse_tstamp (STB_GLOBAL)
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
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81972380)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81972380-ffffffff819723d5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192be50)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff8192be50-ffffffff8192bea5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dcb50)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff819dcb50-ffffffff819dcba5: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_collapse_tstamp(struct sk_buff *skb, const struct sk_buff *next_skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e67d0)
Location: net/ipv4/tcp_output.c:2779
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff819e67d0-ffffffff819e6825: tcp_skb_collapse_tstamp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

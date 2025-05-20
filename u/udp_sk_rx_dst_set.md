# Function: <code>udp_sk_rx_dst_set</code>

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
In net/ipv4/udp.c (ffffffff8178a432)
Location: net/ipv4/udp.c:1654
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff817f7901)
Location: net/ipv4/udp.c:1620
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff818287e9)
Location: net/ipv4/udp.c:1776
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81846fc0)
Location: net/ipv4/udp.c:1935
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81846fc0-ffffffff8184701c: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c6a20)
Location: net/ipv4/udp.c:1934
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff818c6a20-ffffffff818c6a80: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191c3f0)
Location: net/ipv4/udp.c:2017
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8191c3f0-ffffffff8191c44c: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194a9c0)
Location: net/ipv4/udp.c:2103
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8194a9c0-ffffffff8194aa1c: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819af830)
Location: net/ipv4/udp.c:2089
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819af830-ffffffff819af874: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e64c0)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819e64c0-ffffffff819e6504: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad28d0)
Location: net/ipv4/udp.c:2133
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81ad28d0-ffffffff81ad2914: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ade980)
Location: net/ipv4/udp.c:2186
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81ade980-ffffffff81ade9c4: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac9880)
Location: net/ipv4/udp.c:2237
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81ac9880-ffffffff81ac98c4: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b880f0)
Location: net/ipv4/udp.c:2249
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b880f0-ffffffff81b88134: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d19340)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81d19340-ffffffff81d19398: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81edfaf0)
Location: net/ipv4/udp.c:2260
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81edfaf0-ffffffff81edfb48: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3ef30)
Location: net/ipv4/udp.c:2232
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81f3ef30-ffffffff81f3ef82: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82005290)
Location: net/ipv4/udp.c:2205
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff82005290-ffffffff820052e2: udp_sk_rx_dst_set (STB_GLOBAL)
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
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c99950)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffff800010c99950-ffff800010c99a00: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da9d70)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c0da9d70-c0da9e00: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dabfb0)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c000000000dabfb0-c000000000dac05c: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f84be)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffe0007f84be-ffffffe0007f8534: udp_sk_rx_dst_set (STB_GLOBAL)
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
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81986330)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81986330-ffffffff81986374: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193fdf0)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8193fdf0-ffffffff8193fe34: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f0b00)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819f0b00-ffffffff819f0b44: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool udp_sk_rx_dst_set(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fc350)
Location: net/ipv4/udp.c:2125
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819fc350-ffffffff819fc394: udp_sk_rx_dst_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>tcp_v6_send_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff817f06b0)
Location: include/net/ip6_checksum.h:85
Inline: False
```
**Symbols:**

```
ffffffff817f06b0-ffffffff817f0783: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8185f920)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff8185f920-ffffffff8185f9f3: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81891880)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff81891880-ffffffff81891953: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b85a0)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff818b85a0-ffffffff818b8676: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8193b430)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff8193b430-ffffffff8193b506: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81993e90)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff81993e90-ffffffff81993f66: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c9d90)
Location: include/net/ip6_checksum.h:84
Inline: False
```
**Symbols:**

```
ffffffff819c9d90-ffffffff819c9e60: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a38820)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff81a38820-ffffffff81a388ed: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f380)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff81a6f380-ffffffff81a6f44d: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b68760)
Location: include/net/ip6_checksum.h:89
Inline: False
```
**Symbols:**

```
ffffffff81b68760-ffffffff81b6882d: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b76ff0)
Location: net/ipv6/tcp_ipv6.c:1852
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81b76ff0-ffffffff81b770c2: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b65b10)
Location: net/ipv6/tcp_ipv6.c:1882
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81b65b10-ffffffff81b65be2: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1898
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81d40c3a-ffffffff81d40c5a: tcp_v6_send_check.cold (STB_LOCAL)
ffffffff81c2c530-ffffffff81c2c61b: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9840)
Location: net/ipv6/tcp_ipv6.c:1869
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81dc9840-ffffffff81dc98ae: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a7c0)
Location: net/ipv6/tcp_ipv6.c:1880
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81f9a7c0-ffffffff81f9a82e: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb320)
Location: net/ipv6/tcp_ipv6.c:1881
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81ffb320-ffffffff81ffb38e: tcp_v6_send_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff820c8c00)
Location: net/ipv6/tcp_ipv6.c:2045
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff820c8c00-ffffffff820c8c6e: tcp_v6_send_check (STB_GLOBAL)
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
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d36c18)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffff800010d36c18-ffff800010d36d00: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e3b140)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
c0e3b140-c0e3b21c: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e6bec0)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
c000000000e6bec0-c000000000e6bfe8: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe000875f70)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffe000875f70-ffffffe000876030: tcp_v6_send_check (STB_LOCAL)
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
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ea10)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff81a0ea10-ffffffff81a0eadd: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819cb7d0)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff819cb7d0-ffffffff819cb89d: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a79490)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff81a79490-ffffffff81a7955d: tcp_v6_send_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_v6_send_check(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a85c50)
Location: include/net/ip6_checksum.h:80
Inline: False
```
**Symbols:**

```
ffffffff81a85c50-ffffffff81a85d1d: tcp_v6_send_check (STB_LOCAL)
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

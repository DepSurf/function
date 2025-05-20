# Function: <code>tcp_v6_route_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req, bool *strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff817efb50)
Location: net/ipv6/tcp_ipv6.c:700
Inline: False
```
**Symbols:**

```
ffffffff817efb50-ffffffff817efb6d: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req, bool *strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8185e740)
Location: net/ipv6/tcp_ipv6.c:709
Inline: False
```
**Symbols:**

```
ffffffff8185e740-ffffffff8185e75d: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req, bool *strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81890880)
Location: net/ipv6/tcp_ipv6.c:719
Inline: False
```
**Symbols:**

```
ffffffff81890880-ffffffff8189089d: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b6e50)
Location: net/ipv6/tcp_ipv6.c:742
Inline: False
```
**Symbols:**

```
ffffffff818b6e50-ffffffff818b6e65: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81939c80)
Location: net/ipv6/tcp_ipv6.c:744
Inline: False
```
**Symbols:**

```
ffffffff81939c80-ffffffff81939c95: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81991f30)
Location: net/ipv6/tcp_ipv6.c:758
Inline: False
```
**Symbols:**

```
ffffffff81991f30-ffffffff81991f45: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c8780)
Location: net/ipv6/tcp_ipv6.c:762
Inline: False
```
**Symbols:**

```
ffffffff819c8780-ffffffff819c8795: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a37120)
Location: net/ipv6/tcp_ipv6.c:769
Inline: False
```
**Symbols:**

```
ffffffff81a37120-ffffffff81a37135: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d5c0)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffff81a6d5c0-ffffffff81a6d5d5: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b666f0)
Location: net/ipv6/tcp_ipv6.c:820
Inline: False
```
**Symbols:**

```
ffffffff81b666f0-ffffffff81b66705: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b771d0)
Location: net/ipv6/tcp_ipv6.c:831
Inline: False
```
**Symbols:**

```
ffffffff81b771d0-ffffffff81b77230: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b65bf0)
Location: net/ipv6/tcp_ipv6.c:846
Inline: False
```
**Symbols:**

```
ffffffff81b65bf0-ffffffff81b65d28: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c620)
Location: net/ipv6/tcp_ipv6.c:849
Inline: False
```
**Symbols:**

```
ffffffff81c2c620-ffffffff81c2c758: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9b50)
Location: net/ipv6/tcp_ipv6.c:802
Inline: False
```
**Symbols:**

```
ffffffff81dc9b50-ffffffff81dc9c8d: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ab20)
Location: net/ipv6/tcp_ipv6.c:809
Inline: False
```
**Symbols:**

```
ffffffff81f9ab20-ffffffff81f9ac5d: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb680)
Location: net/ipv6/tcp_ipv6.c:806
Inline: False
```
**Symbols:**

```
ffffffff81ffb680-ffffffff81ffb7bd: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff820c8f70)
Location: net/ipv6/tcp_ipv6.c:819
Inline: False
```
**Symbols:**

```
ffffffff820c8f70-ffffffff820c90be: tcp_v6_route_req (STB_LOCAL)
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
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d35e40)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffff800010d35e40-ffff800010d35e88: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e38ca4)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
c0e38ca4-c0e38cc4: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e68050)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
c000000000e68050-c000000000e68088: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe0008733cc)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffe0008733cc-ffffffe000873408: tcp_v6_route_req (STB_LOCAL)
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
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cc50)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffff81a0cc50-ffffffff81a0cc65: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c9a10)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffff819c9a10-ffffffff819c9a25: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a776d0)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffff81a776d0-ffffffff81a776e5: tcp_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *tcp_v6_route_req(const struct sock *sk, struct flowi *fl, const struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a83e40)
Location: net/ipv6/tcp_ipv6.c:771
Inline: False
```
**Symbols:**

```
ffffffff81a83e40-ffffffff81a83e55: tcp_v6_route_req (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *strict</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, fl, req</code> ➡️ <code>sk, skb, fl, req</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct request_sock *req</code> ➡️ <code>struct request_sock *req</code>
</li>
</ul>
</details>
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

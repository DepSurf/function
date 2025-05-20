# Function: <code>tcp_conn_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176dad0)
Location: net/ipv4/tcp_input.c:6156
Inline: False
```
**Symbols:**

```
ffffffff8176dad0-ffffffff8176e49c: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dbe20)
Location: net/ipv4/tcp_input.c:6209
Inline: False
```
**Symbols:**

```
ffffffff817dbe20-ffffffff817dc8f0: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180bef0)
Location: net/ipv4/tcp_input.c:6301
Inline: False
```
**Symbols:**

```
ffffffff8180bef0-ffffffff8180c9ee: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182c090)
Location: net/ipv4/tcp_input.c:6299
Inline: False
```
**Symbols:**

```
ffffffff8182c090-ffffffff8182cc1d: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818aaf20)
Location: net/ipv4/tcp_input.c:6196
Inline: False
```
**Symbols:**

```
ffffffff818aaf20-ffffffff818abb17: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6360
Inline: False
```
**Symbols:**

```
ffffffff8190615d-ffffffff81906189: tcp_conn_request.cold.79 (STB_LOCAL)
ffffffff81900420-ffffffff81900fc8: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6411
Inline: False
```
**Symbols:**

```
ffffffff819342ff-ffffffff8193432b: tcp_conn_request.cold.85 (STB_LOCAL)
ffffffff8192e580-ffffffff8192f18d: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6469
Inline: False
```
**Symbols:**

```
ffffffff81998068-ffffffff8199809c: tcp_conn_request.cold (STB_LOCAL)
ffffffff81991b60-ffffffff819926be: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c8760)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffff819c8760-ffffffff819c91f8: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab3c70)
Location: net/ipv4/tcp_input.c:6612
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff81ab3c70-ffffffff81ab4710: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abe5d0)
Location: net/ipv4/tcp_input.c:6762
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff81abe5d0-ffffffff81abf045: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaa920)
Location: net/ipv4/tcp_input.c:6771
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff81aaa920-ffffffff81aab4e0: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6806
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff81d3aa00-ffffffff81d3aade: tcp_conn_request.cold (STB_LOCAL)
ffffffff81b66d10-ffffffff81b678f3: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6892
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff81f072a8-ffffffff81f07386: tcp_conn_request.cold (STB_LOCAL)
ffffffff81cf5d40-ffffffff81cf69a4: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6922
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff820aed3c-ffffffff820aee1a: tcp_conn_request.cold (STB_LOCAL)
ffffffff81eba750-ffffffff81ebb3b4: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6929
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff82130192-ffffffff82130212: tcp_conn_request.cold (STB_LOCAL)
ffffffff81f18be0-ffffffff81f19840: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:7089
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
**Symbols:**

```
ffffffff82211cbb-ffffffff82211d3b: tcp_conn_request.cold (STB_LOCAL)
ffffffff81fdd3a0-ffffffff81fde092: tcp_conn_request (STB_GLOBAL)
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
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7a3b8)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffff800010c7a3b8-ffff800010c7ad60: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d87e50)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
c0d87e50-c0d8890c: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d84ed0)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
c000000000d84ed0-c000000000d85b40: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007de0e0)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffe0007de0e0-ffffffe0007dea2c: tcp_conn_request (STB_GLOBAL)
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
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819685d0)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffff819685d0-ffffffff81969068: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819220c0)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffff819220c0-ffffffff81922b58: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d2da0)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffff819d2da0-ffffffff819d3838: tcp_conn_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_conn_request(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dc940)
Location: net/ipv4/tcp_input.c:6553
Inline: False
```
**Symbols:**

```
ffffffff819dc940-ffffffff819dd3fd: tcp_conn_request (STB_GLOBAL)
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

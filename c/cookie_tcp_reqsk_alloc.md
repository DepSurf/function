# Function: <code>cookie_tcp_reqsk_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b15520)
Location: net/ipv4/syncookies.c:285
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b15520-ffffffff81b1561e: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b03330)
Location: net/ipv4/syncookies.c:285
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b03330-ffffffff81b0342e: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (0)
Location: net/ipv4/syncookies.c:285
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81d3ec29-ffffffff81d3ec51: cookie_tcp_reqsk_alloc.cold (STB_LOCAL)
ffffffff81bc5590-ffffffff81bc56b1: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (0)
Location: net/ipv4/syncookies.c:283
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f0b574-ffffffff81f0b59e: cookie_tcp_reqsk_alloc.cold (STB_LOCAL)
ffffffff81d5a760-ffffffff81d5a89b: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (0)
Location: net/ipv4/syncookies.c:283
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff820b2df9-ffffffff820b2e23: cookie_tcp_reqsk_alloc.cold (STB_LOCAL)
ffffffff81f24ba0-ffffffff81f24cdd: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (0)
Location: net/ipv4/syncookies.c:283
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff82133fa1-ffffffff82133fcb: cookie_tcp_reqsk_alloc.cold (STB_LOCAL)
ffffffff81f84730-ffffffff81f8486d: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct request_sock *cookie_tcp_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk, struct sk_buff *skb, struct tcp_options_received *tcp_opt, int mss, u32 tsoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (0)
Location: net/ipv4/syncookies.c:307
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff82215983-ffffffff822159b3: cookie_tcp_reqsk_alloc.cold (STB_LOCAL)
ffffffff8204aaf0-ffffffff8204ae14: cookie_tcp_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcp_request_sock_ops *af_ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, sk, skb</code> ➡️ <code>ops, af_ops, sk, skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tcp_options_received *tcp_opt</code>
</li>
<li>
<b>Param added. </b>
<code>int mss</code>
</li>
<li>
<b>Param added. </b>
<code>u32 tsoff</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct tcp_request_sock_ops *af_ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, af_ops, sk, skb</code> ➡️ <code>ops, sk, skb, tcp_opt, mss, tsoff</code>
</li>
</ul>
</details>
</li>
</ul>

# Function: <code>mptcp_get_reset_option</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5000)
Location: net/mptcp/options.c:1343
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81bb5000-ffffffff81bb5046: mptcp_get_reset_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c83840)
Location: net/mptcp/options.c:1496
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81c83840-ffffffff81c83886: mptcp_get_reset_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e29810)
Location: net/mptcp/options.c:1617
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81e29810-ffffffff81e29860: mptcp_get_reset_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff820018f0)
Location: net/mptcp/options.c:1626
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff820018f0-ffffffff82001940: mptcp_get_reset_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207ddb0)
Location: net/mptcp/options.c:1636
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8207ddb0-ffffffff8207de00: mptcp_get_reset_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__be32 mptcp_get_reset_option(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82152ff0)
Location: net/mptcp/options.c:1639
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff82152ff0-ffffffff82153040: mptcp_get_reset_option (STB_GLOBAL)
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

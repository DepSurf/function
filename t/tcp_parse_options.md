# Function: <code>tcp_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_parse_options(const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c6d0)
Location: net/ipv4/tcp_input.c:3697
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8176c6d0-ffffffff8176cacc: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_parse_options(const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d9c60)
Location: net/ipv4/tcp_input.c:3755
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817d9c60-ffffffff817da058: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_parse_options(const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808280)
Location: net/ipv4/tcp_input.c:3771
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81808280-ffffffff81808588: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81828650)
Location: net/ipv4/tcp_input.c:3727
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81828650-ffffffff8182896b: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a7a70)
Location: net/ipv4/tcp_input.c:3691
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818a7a70-ffffffff818a7ddb: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3775
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81906106-ffffffff81906140: tcp_parse_options.cold.77 (STB_LOCAL)
ffffffff818fcc90-ffffffff818fcf95: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3774
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819342a8-ffffffff819342e2: tcp_parse_options.cold.83 (STB_LOCAL)
ffffffff8192ae00-ffffffff8192b105: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3789
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81997f44-ffffffff81997f7f: tcp_parse_options.cold (STB_LOCAL)
ffffffff8198e090-ffffffff8198e3ad: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819ceabe-ffffffff819ceaf9: tcp_parse_options.cold (STB_LOCAL)
ffffffff819c4cc0-ffffffff819c4fdd: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3833
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81abac94-ffffffff81abacce: tcp_parse_options.cold (STB_LOCAL)
ffffffff81ab02d0-ffffffff81ab05f4: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3962
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81c3266c-ffffffff81c326a6: tcp_parse_options.cold (STB_LOCAL)
ffffffff81abb360-ffffffff81abb69f: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3969
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81c2493c-ffffffff81c24976: tcp_parse_options.cold (STB_LOCAL)
ffffffff81aa6310-ffffffff81aa6650: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4003
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81d3a790-ffffffff81d3a7ca: tcp_parse_options.cold (STB_LOCAL)
ffffffff81b62700-ffffffff81b62a40: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4021
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f06fa6-ffffffff81f06fdb: tcp_parse_options.cold (STB_LOCAL)
ffffffff81cf0d90-ffffffff81cf10eb: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5a10)
Location: net/ipv4/tcp_input.c:4035
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81eb5a10-ffffffff81eb5d99: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13e40)
Location: net/ipv4/tcp_input.c:4040
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f13e40-ffffffff81f141b6: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd8320)
Location: net/ipv4/tcp_input.c:4118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81fd8320-ffffffff81fd8696: tcp_parse_options (STB_GLOBAL)
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
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c77608)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010c77608-ffff800010c77954: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d85e34)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0d85e34-c0d86240: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7fb60)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000d7fb60-c000000000d80064: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dace0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe0007dace0-ffffffe0007db070: tcp_parse_options (STB_GLOBAL)
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
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8196e92e-ffffffff8196e969: tcp_parse_options.cold (STB_LOCAL)
ffffffff81964b30-ffffffff81964e4d: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8192841e-ffffffff81928459: tcp_parse_options.cold (STB_LOCAL)
ffffffff8191e620-ffffffff8191e93d: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819d90fe-ffffffff819d9139: tcp_parse_options.cold (STB_LOCAL)
ffffffff819cf300-ffffffff819cf61d: tcp_parse_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tcp_parse_options(const struct net *net, const struct sk_buff *skb, struct tcp_options_received *opt_rx, int estab, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819e2d69-ffffffff819e2da4: tcp_parse_options.cold (STB_LOCAL)
ffffffff819d8e90-ffffffff819d91ad: tcp_parse_options (STB_GLOBAL)
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
<b>Param added. </b>
<code>const struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, opt_rx, estab, foc</code> ➡️ <code>net, skb, opt_rx, estab, foc</code>
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

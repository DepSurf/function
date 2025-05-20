# Function: <code>inet_reqsk_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176b2a0)
Location: net/ipv4/tcp_input.c:6088
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8176b2a0-ffffffff8176b345: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d7a30)
Location: net/ipv4/tcp_input.c:6137
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817d7a30-ffffffff817d7b32: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818079d0)
Location: net/ipv4/tcp_input.c:6229
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818079d0-ffffffff81807ad2: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818283b0)
Location: net/ipv4/tcp_input.c:6227
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818283b0-ffffffff8182849d: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a7880)
Location: net/ipv4/tcp_input.c:6125
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818a7880-ffffffff818a79a8: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fc9d0)
Location: net/ipv4/tcp_input.c:6289
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818fc9d0-ffffffff818fcb04: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192ab40)
Location: net/ipv4/tcp_input.c:6340
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8192ab40-ffffffff8192ac76: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198dd90)
Location: net/ipv4/tcp_input.c:6398
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8198dd90-ffffffff8198dea9: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c4960)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819c4960-ffffffff819c4a79: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0a90)
Location: net/ipv4/tcp_input.c:6513
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81ab0a90-ffffffff81ab0bba: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abbae0)
Location: net/ipv4/tcp_input.c:6649
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81abbae0-ffffffff81abbc0a: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6aa0)
Location: net/ipv4/tcp_input.c:6658
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81aa6aa0-ffffffff81aa6bc6: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b630a0)
Location: net/ipv4/tcp_input.c:6693
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81b630a0-ffffffff81b631c6: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf1d50)
Location: net/ipv4/tcp_input.c:6776
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81cf1d50-ffffffff81cf1e7d: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb65c0)
Location: net/ipv4/tcp_input.c:6798
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
```
**Symbols:**

```
ffffffff81eb65c0-ffffffff81eb66ed: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f149e0)
Location: net/ipv4/tcp_input.c:6805
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
```
**Symbols:**

```
ffffffff81f149e0-ffffffff81f14b09: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd8f00)
Location: net/ipv4/tcp_input.c:6965
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
  - net/mptcp/subflow.c:mptcp_subflow_reqsk_alloc
```
**Symbols:**

```
ffffffff81fd8f00-ffffffff81fd9033: inet_reqsk_alloc (STB_GLOBAL)
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
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c773e0)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010c773e0-ffff800010c774a4: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d85954)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0d85954-c0d85a3c: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7f7b0)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000d7f7b0-c000000000d7f8e4: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007da566)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe0007da566-ffffffe0007da630: inet_reqsk_alloc (STB_GLOBAL)
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
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819647d0)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819647d0-ffffffff819648e9: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191e2c0)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8191e2c0-ffffffff8191e3d9: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cefa0)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819cefa0-ffffffff819cf0b9: inet_reqsk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request_sock *inet_reqsk_alloc(const struct request_sock_ops *ops, struct sock *sk_listener, bool attach_listener);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8b30)
Location: net/ipv4/tcp_input.c:6454
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819d8b30-ffffffff819d8c49: inet_reqsk_alloc (STB_GLOBAL)
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

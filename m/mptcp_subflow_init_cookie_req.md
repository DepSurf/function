# Function: <code>mptcp_subflow_init_cookie_req</code>

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
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc24e0)
Location: net/mptcp/subflow.c:192
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81bc24e0-ffffffff81bc2634: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb1000)
Location: net/mptcp/subflow.c:237
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81bb1000-ffffffff81bb1125: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c7f0f0)
Location: net/mptcp/subflow.c:242
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81c7f0f0-ffffffff81c7f26a: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e249e0)
Location: net/mptcp/subflow.c:244
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81e249e0-ffffffff81e24b71: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffc4d0)
Location: net/mptcp/subflow.c:243
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff81ffc4d0-ffffffff81ffc661: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff82078820)
Location: net/mptcp/subflow.c:244
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff82078820-ffffffff820789af: mptcp_subflow_init_cookie_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_subflow_init_cookie_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214dbf0)
Location: net/mptcp/subflow.c:244
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
**Symbols:**

```
ffffffff8214dbf0-ffffffff8214dd7f: mptcp_subflow_init_cookie_req (STB_GLOBAL)
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

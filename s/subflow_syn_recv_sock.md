# Function: <code>subflow_syn_recv_sock</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81baec10)
Location: net/mptcp/subflow.c:424
Inline: False
```
**Symbols:**

```
ffffffff81baec10-ffffffff81baf0e1: subflow_syn_recv_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc1770)
Location: net/mptcp/subflow.c:535
Inline: False
```
**Symbols:**

```
ffffffff81bc1770-ffffffff81bc1d02: subflow_syn_recv_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb2040)
Location: net/mptcp/subflow.c:615
Inline: False
```
**Symbols:**

```
ffffffff81bb2040-ffffffff81bb266f: subflow_syn_recv_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:628
Inline: False
```
**Symbols:**

```
ffffffff81c802d0-ffffffff81c808e8: subflow_syn_recv_sock (STB_LOCAL)
ffffffff81d4398e-ffffffff81d43a8e: subflow_syn_recv_sock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:674
Inline: False
```
**Symbols:**

```
ffffffff81e25f50-ffffffff81e26579: subflow_syn_recv_sock (STB_LOCAL)
ffffffff81f10495-ffffffff81f10593: subflow_syn_recv_sock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:740
Inline: False
```
**Symbols:**

```
ffffffff81fff050-ffffffff81fff69b: subflow_syn_recv_sock (STB_LOCAL)
ffffffff820b68f1-ffffffff820b69c5: subflow_syn_recv_sock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:741
Inline: False
```
**Symbols:**

```
ffffffff8207b270-ffffffff8207b76b: subflow_syn_recv_sock (STB_LOCAL)
ffffffff82137c6f-ffffffff82137d39: subflow_syn_recv_sock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *subflow_syn_recv_sock(const struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct dst_entry *dst, struct request_sock *req_unhash, bool *own_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:766
Inline: False
```
**Symbols:**

```
ffffffff82150850-ffffffff82150d3c: subflow_syn_recv_sock (STB_LOCAL)
ffffffff82219b51-ffffffff82219c1b: subflow_syn_recv_sock.cold (STB_LOCAL)
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

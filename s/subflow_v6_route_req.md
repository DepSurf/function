# Function: <code>subflow_v6_route_req</code>

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
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc2a10)
Location: net/mptcp/subflow.c:258
Inline: False
```
**Symbols:**

```
ffffffff81bc2a10-ffffffff81bc2ab1: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb1af0)
Location: net/mptcp/subflow.c:301
Inline: False
```
**Symbols:**

```
ffffffff81bb1af0-ffffffff81bb1b91: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c7ff60)
Location: net/mptcp/subflow.c:309
Inline: False
```
**Symbols:**

```
ffffffff81c7ff60-ffffffff81c80059: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e259a0)
Location: net/mptcp/subflow.c:311
Inline: False
```
**Symbols:**

```
ffffffff81e259a0-ffffffff81e25ab1: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffd4e0)
Location: net/mptcp/subflow.c:351
Inline: False
```
**Symbols:**

```
ffffffff81ffd4e0-ffffffff81ffd5f1: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff820797b0)
Location: net/mptcp/subflow.c:352
Inline: False
```
**Symbols:**

```
ffffffff820797b0-ffffffff820798c1: subflow_v6_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *subflow_v6_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214ec00)
Location: net/mptcp/subflow.c:352
Inline: False
```
**Symbols:**

```
ffffffff8214ec00-ffffffff8214ed11: subflow_v6_route_req (STB_LOCAL)
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

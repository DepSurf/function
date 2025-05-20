# Function: <code>subflow_v4_route_req</code>

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
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc2ac0)
Location: net/mptcp/subflow.c:232
Inline: False
```
**Symbols:**

```
ffffffff81bc2ac0-ffffffff81bc2b61: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb1ba0)
Location: net/mptcp/subflow.c:275
Inline: False
```
**Symbols:**

```
ffffffff81bb1ba0-ffffffff81bb1c41: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c7fe60)
Location: net/mptcp/subflow.c:283
Inline: False
```
**Symbols:**

```
ffffffff81c7fe60-ffffffff81c7ff59: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e25880)
Location: net/mptcp/subflow.c:285
Inline: False
```
**Symbols:**

```
ffffffff81e25880-ffffffff81e25991: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffd610)
Location: net/mptcp/subflow.c:284
Inline: False
```
**Symbols:**

```
ffffffff81ffd610-ffffffff81ffd721: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff820798e0)
Location: net/mptcp/subflow.c:285
Inline: False
```
**Symbols:**

```
ffffffff820798e0-ffffffff820799f1: subflow_v4_route_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *subflow_v4_route_req(const struct sock *sk, struct sk_buff *skb, struct flowi *fl, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214ed30)
Location: net/mptcp/subflow.c:285
Inline: False
```
**Symbols:**

```
ffffffff8214ed30-ffffffff8214ee41: subflow_v4_route_req (STB_LOCAL)
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

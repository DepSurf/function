# Function: <code>subflow_check_req</code>

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
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc2760)
Location: net/mptcp/subflow.c:110
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81bc2760-ffffffff81bc2a10: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb16a0)
Location: net/mptcp/subflow.c:135
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81bb16a0-ffffffff81bb1aed: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c7f8f0)
Location: net/mptcp/subflow.c:137
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81c7f8f0-ffffffff81c7fcd2: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e252b0)
Location: net/mptcp/subflow.c:139
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81e252b0-ffffffff81e256c1: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffcee0)
Location: net/mptcp/subflow.c:138
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81ffcee0-ffffffff81ffd2f1: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff820791b0)
Location: net/mptcp/subflow.c:139
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff820791b0-ffffffff820795c1: subflow_check_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int subflow_check_req(struct request_sock *req, const struct sock *sk_listener, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214e600)
Location: net/mptcp/subflow.c:139
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff8214e600-ffffffff8214ea11: subflow_check_req (STB_LOCAL)
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

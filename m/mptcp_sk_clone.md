# Function: <code>mptcp_sk_clone</code>

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
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad690)
Location: net/mptcp/protocol.c:1430
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bad690-ffffffff81bad8e8: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bc0710)
Location: net/mptcp/protocol.c:2671
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bc0710-ffffffff81bc088e: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb04b0)
Location: net/mptcp/protocol.c:2747
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bb04b0-ffffffff81bb0644: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7e360)
Location: net/mptcp/protocol.c:2804
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81c7e360-ffffffff81c7e50c: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e23770)
Location: net/mptcp/protocol.c:2958
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81e23770-ffffffff81e2391a: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *mptcp_sk_clone(const struct sock *sk, const struct mptcp_options_received *mp_opt, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffaf00)
Location: net/mptcp/protocol.c:3054
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81ffaf00-ffffffff81ffb034: mptcp_sk_clone (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>

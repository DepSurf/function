# Function: <code>mptcp_token_accept</code>

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
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc5f00)
Location: net/mptcp/token.c:190
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bc5f00-ffffffff81bc5fc8: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6a60)
Location: net/mptcp/token.c:190
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bb6a60-ffffffff81bb6b28: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85a90)
Location: net/mptcp/token.c:189
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81c85a90-ffffffff81c85b58: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2bd20)
Location: net/mptcp/token.c:189
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81e2bd20-ffffffff81e2bdf6: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82003f30)
Location: net/mptcp/token.c:189
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff82003f30-ffffffff82004006: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff820800c0)
Location: net/mptcp/token.c:191
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
**Symbols:**

```
ffffffff820800c0-ffffffff820801d3: mptcp_token_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_token_accept(struct mptcp_subflow_request_sock *req, struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff821555b0)
Location: net/mptcp/token.c:191
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
**Symbols:**

```
ffffffff821555b0-ffffffff821556c3: mptcp_token_accept (STB_GLOBAL)
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

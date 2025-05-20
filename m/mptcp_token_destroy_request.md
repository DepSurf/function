# Function: <code>mptcp_token_destroy_request</code>

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
void mptcp_token_destroy_request(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb1d00)
Location: net/mptcp/token.c:178
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff81bb1d00-ffffffff81bb1d38: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc6030)
Location: net/mptcp/token.c:342
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff81bc6030-ffffffff81bc60de: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6b90)
Location: net/mptcp/token.c:342
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff81bb6b90-ffffffff81bb6c3e: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85bc0)
Location: net/mptcp/token.c:346
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff81c85bc0-ffffffff81c85c6e: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2be80)
Location: net/mptcp/token.c:346
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff81e2be80-ffffffff81e2bf46: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff820040b0)
Location: net/mptcp/token.c:346
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff820040b0-ffffffff82004176: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82080280)
Location: net/mptcp/token.c:350
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff82080280-ffffffff82080346: mptcp_token_destroy_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_token_destroy_request(struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82155770)
Location: net/mptcp/token.c:350
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_req_destructor
  - net/mptcp/subflow.c:subflow_req_destructor
```
**Symbols:**

```
ffffffff82155770-ffffffff82155836: mptcp_token_destroy_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_sock *req</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 token</code>
</li>
</ul>
</details>
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

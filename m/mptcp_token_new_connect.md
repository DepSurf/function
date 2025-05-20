# Function: <code>mptcp_token_new_connect</code>

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
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb1b10)
Location: net/mptcp/token.c:97
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_rebuild_header
```
**Symbols:**

```
ffffffff81bb1b10-ffffffff81bb1c16: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc5dd0)
Location: net/mptcp/token.c:152
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
```
**Symbols:**

```
ffffffff81bc5dd0-ffffffff81bc5ef3: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6930)
Location: net/mptcp/token.c:152
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
```
**Symbols:**

```
ffffffff81bb6930-ffffffff81bb6a55: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85960)
Location: net/mptcp/token.c:151
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
```
**Symbols:**

```
ffffffff81c85960-ffffffff81c85a82: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2bbd0)
Location: net/mptcp/token.c:151
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
```
**Symbols:**

```
ffffffff81e2bbd0-ffffffff81e2bd1d: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82003dd0)
Location: net/mptcp/token.c:151
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_connect
```
**Symbols:**

```
ffffffff82003dd0-ffffffff82003f1d: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff8207ff20)
Location: net/mptcp/token.c:151
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_connect
```
**Symbols:**

```
ffffffff8207ff20-ffffffff820800a6: mptcp_token_new_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_token_new_connect(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82155410)
Location: net/mptcp/token.c:151
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_connect
```
**Symbols:**

```
ffffffff82155410-ffffffff82155596: mptcp_token_new_connect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *ssk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sock *sk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

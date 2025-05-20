# Function: <code>mptcp_fastopen_subflow_synack_set_params</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_fastopen_subflow_synack_set_params(struct mptcp_subflow_context *subflow, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/fastopen.c (ffffffff8200eea0)
Location: net/mptcp/fastopen.c:9
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
```
**Symbols:**

```
ffffffff8200eea0-ffffffff8200f025: mptcp_fastopen_subflow_synack_set_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_fastopen_subflow_synack_set_params(struct mptcp_subflow_context *subflow, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/fastopen.c (ffffffff8208ba90)
Location: net/mptcp/fastopen.c:9
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
```
**Symbols:**

```
ffffffff8208ba90-ffffffff8208bc12: mptcp_fastopen_subflow_synack_set_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_fastopen_subflow_synack_set_params(struct mptcp_subflow_context *subflow, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/fastopen.c (ffffffff82161890)
Location: net/mptcp/fastopen.c:9
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_send_synack
  - net/mptcp/subflow.c:subflow_v4_send_synack
```
**Symbols:**

```
ffffffff82161890-ffffffff82161a1c: mptcp_fastopen_subflow_synack_set_params (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

# Function: <code>mptcp_token_exists</code>

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
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc5fd0)
Location: net/mptcp/token.c:207
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81bc5fd0-ffffffff81bc6030: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6b30)
Location: net/mptcp/token.c:207
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81bb6b30-ffffffff81bb6b90: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85b60)
Location: net/mptcp/token.c:206
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81c85b60-ffffffff81c85bc0: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2be00)
Location: net/mptcp/token.c:206
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81e2be00-ffffffff81e2be76: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82004020)
Location: net/mptcp/token.c:206
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff82004020-ffffffff82004096: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff820801f0)
Location: net/mptcp/token.c:210
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff820801f0-ffffffff82080266: mptcp_token_exists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_token_exists(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff821556e0)
Location: net/mptcp/token.c:210
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff821556e0-ffffffff82155756: mptcp_token_exists (STB_GLOBAL)
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

# Function: <code>__token_bucket_busy</code>

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
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc59a0)
Location: net/mptcp/token.c:80
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81bc59a0-ffffffff81bc59fe: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6520)
Location: net/mptcp/token.c:80
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81bb6520-ffffffff81bb657e: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85530)
Location: net/mptcp/token.c:79
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81c85530-ffffffff81c8558e: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2b720)
Location: net/mptcp/token.c:79
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81e2b720-ffffffff81e2b796: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff820038e0)
Location: net/mptcp/token.c:79
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff820038e0-ffffffff82003956: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff8207fa70)
Location: net/mptcp/token.c:79
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff8207fa70-ffffffff8207fae6: __token_bucket_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __token_bucket_busy(struct token_bucket *t, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82154f60)
Location: net/mptcp/token.c:79
Inline: False
Direct callers:
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff82154f60-ffffffff82154fd6: __token_bucket_busy (STB_LOCAL)
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

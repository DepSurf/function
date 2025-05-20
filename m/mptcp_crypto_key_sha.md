# Function: <code>mptcp_crypto_key_sha</code>

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
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff81bb1d80)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81bb1d80-ffffffff81bb1e5a: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff81bc6190)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81bc6190-ffffffff81bc6208: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff81bb6cf0)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81bb6cf0-ffffffff81bb6d68: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff81c85d20)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81c85d20-ffffffff81c85d98: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff81e2c020)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81e2c020-ffffffff81e2c0c4: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82004270)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_fully_established
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff82004270-ffffffff82004314: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82080480)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_fully_established
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff82080480-ffffffff82080524: mptcp_crypto_key_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 *token, u64 *idsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82155970)
Location: net/mptcp/crypto.c:31
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_fully_established
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff82155970-ffffffff82155a14: mptcp_crypto_key_sha (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

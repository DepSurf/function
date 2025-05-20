# Function: <code>mptcp_crypto_hmac_sha</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/crypto.c (0)
Location: net/mptcp/crypto.c:47
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_addr
```
**Symbols:**

```
ffffffff81bb2112-ffffffff81bb211e: mptcp_crypto_hmac_sha.cold (STB_LOCAL)
ffffffff81bb1e60-ffffffff81bb2112: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/crypto.c (0)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81c33f64-ffffffff81c33f70: mptcp_crypto_hmac_sha.cold (STB_LOCAL)
ffffffff81bc6210-ffffffff81bc63fb: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/crypto.c (0)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff81c262ab-ffffffff81c262b7: mptcp_crypto_hmac_sha.cold (STB_LOCAL)
ffffffff81bb6d70-ffffffff81bb6f5d: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/crypto.c (0)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff81d43e3c-ffffffff81d43e48: mptcp_crypto_hmac_sha.cold (STB_LOCAL)
ffffffff81c85da0-ffffffff81c86181: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/crypto.c (0)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff81f1096e-ffffffff81f1097a: mptcp_crypto_hmac_sha.cold (STB_LOCAL)
ffffffff81e2c0d0-ffffffff81e2c505: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82004330)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff82004330-ffffffff82004771: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82080540)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff82080540-ffffffff8208091b: mptcp_crypto_hmac_sha (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 *msg, int len, void *hmac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/crypto.c (ffffffff82155a30)
Location: net/mptcp/crypto.c:44
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:add_addr_generate_hmac
```
**Symbols:**

```
ffffffff82155a30-ffffffff82155e0b: mptcp_crypto_hmac_sha (STB_GLOBAL)
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

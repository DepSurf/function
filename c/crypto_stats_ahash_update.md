# Function: <code>crypto_stats_ahash_update</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81477ed0)
Location: crypto/algapi.c:1208
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff81477ed0-ffffffff81477f1c: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a5b50)
Location: crypto/algapi.c:1177
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814a5b50-ffffffff814a5b9d: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c08a0)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814c08a0-ffffffff814c08ed: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81521000)
Location: crypto/algapi.c:1159
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff81521000-ffffffff81521068: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153df70)
Location: crypto/algapi.c:1178
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff8153df70-ffffffff8153dfd8: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81546650)
Location: crypto/algapi.c:1178
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff81546650-ffffffff815466b8: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a6dc0)
Location: crypto/algapi.c:1160
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff815a6dc0-ffffffff815a6e28: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164dd60)
Location: crypto/algapi.c:1202
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff8164dd60-ffffffff8164ddec: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff817070d0)
Location: crypto/algapi.c:1150
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
**Symbols:**

```
ffffffff817070d0-ffffffff8170715c: crypto_stats_ahash_update (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105ba1d8)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffff8000105ba1d8-ffff8000105ba284: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c07689a4)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
```
**Symbols:**

```
c07689a4-c0768a48: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c000000000740960)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
c000000000740960-c000000000740a54: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe000400498)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffe000400498-ffffffe00040052c: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b8e80)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814b8e80-ffffffff814b8ecd: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a98a0)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814a98a0-ffffffff814a98ed: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b4f10)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814b4f10-ffffffff814b4f5d: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cd990)
Location: crypto/algapi.c:1187
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash_update
  - lib/iov_iter.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814cd990-ffffffff814cd9dd: crypto_stats_ahash_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

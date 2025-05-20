# Function: <code>crypto_ahash_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81397e13)
Location: include/crypto/hash.h:470
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d4979)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e7fe6)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d956)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813ec3c9)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818186f6)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f9a5)
Location: include/crypto/hash.h:493
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f8783)
Location: include/crypto/hash.h:499
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81838d46)
Location: include/crypto/hash.h:499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b603d)
Location: include/crypto/hash.h:499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81420b05)
Location: include/crypto/hash.h:503
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81438aac)
Location: include/crypto/hash.h:503
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8592)
Location: include/crypto/hash.h:503
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938dcb)
Location: include/crypto/hash.h:503
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81452fa9)
Location: include/crypto/hash.h:502
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146b9f2)
Location: include/crypto/hash.h:502
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eb46)
Location: include/crypto/hash.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992637)
Location: include/crypto/hash.h:502
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81470111)
Location: include/crypto/hash.h:506
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81488f52)
Location: include/crypto/hash.h:506
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193cf76)
Location: include/crypto/hash.h:506
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8d77)
Location: include/crypto/hash.h:506
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149dafe)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b6bfd)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a13c6)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3772b)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813501f0)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f3e)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814cfe1d)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8076)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e255)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81396b64)
Location: include/crypto/hash.h:518
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f6d)
Location: include/crypto/hash.h:518
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8152effd)
Location: include/crypto/hash.h:518
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4066)
Location: include/crypto/hash.h:518
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6747e)
Location: include/crypto/hash.h:518
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813a8794)
Location: include/crypto/hash.h:526
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153412d)
Location: include/crypto/hash.h:526
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154bf7d)
Location: include/crypto/hash.h:526
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfaf6)
Location: include/crypto/hash.h:526
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75c7e)
Location: include/crypto/hash.h:526
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813af804)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d11a)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8155456d)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abac46)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b650a6)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813ff3f4)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf9a)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b559d)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77f96)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d2e6)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81472fc1)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f74)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165e70c)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07bb7)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca6fc)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81504e01)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ee4)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8171843c)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd517)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b736)
Location: include/crypto/hash.h:528
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff817330e8)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81753dac)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c1d7)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffae9e)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int crypto_ahash_init(struct ahash_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/ahash.c (0)
Location: crypto/ahash.c:269
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/gcm.c:gcm_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_parse_crypto
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/ipv4/tcp_ao.c:tcp_ao_calc_traffic_key
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff821d25a9-ffffffff821d25be: crypto_ahash_init.cold (STB_LOCAL)
ffffffff81787a50-ffffffff81787acc: crypto_ahash_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffff800010411e3c)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02f8)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105ccc7c)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ad6c)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37c10)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c05de4a8)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa28)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c077a1ac)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (c0d99644)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c0e38824)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c00000000051fa74)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fdc0)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9982c)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69130)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffe0002b9f56)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f8a)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe000410b1e)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec28a)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874044)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813487d0)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b051e)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c83fd)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977ee6)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d8e5)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813394b0)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f3e)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b8e1d)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819319a6)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca6a5)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813462a0)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac5ae)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c448d)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e26b6)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78365)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81359580)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4ffe)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dcf5d)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec406)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ad5)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

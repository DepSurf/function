# Function: <code>crypto_free_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff811d7d9f)
Location: include/linux/crypto.h:621
Inline: True
```
```
In fs/ext4/crypto_key.c (ffffffff812e58fc)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_key.c:ext4_free_crypt_info
```
```
In fs/ecryptfs/crypto.c (ffffffff8130597a)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
```
```
In fs/ecryptfs/keystore.c (ffffffff81308f65)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81f98255)
Location: include/linux/crypto.h:621
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a0d2d)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_exit
```
```
In crypto/skcipher.c (ffffffff813a1c6d)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
```
```
In crypto/crypto_null.c (ffffffff813a5225)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/ecb.c (ffffffff813a904d)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813a921d)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817826d1)
Location: include/linux/crypto.h:621
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In mm/zswap.c (ffffffff811f5e9f)
Location: include/linux/crypto.h:596
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de33d)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff813e701d)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813e71dd)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff813e85c1)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e8c3d)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff813eb776)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efe77)
Location: include/linux/crypto.h:596
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff81206912)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In crypto/skcipher.c (ffffffff813f5efd)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff813ffdcd)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813fffbd)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff814011fe)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8140224d)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff81404ec6)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820887)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff81212032)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keyinfo.c (ffffffff812ad81e)
Location: include/linux/crypto.h:599
Inline: True
```
```
In crypto/skcipher.c (ffffffff8140228d)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff8140d0dd)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff8140d2cd)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8140e68e)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8140f36d)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff81412696)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840d97)
Location: include/linux/crypto.h:599
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff8122ca02)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keyinfo.c (ffffffff812d0d0e)
Location: include/linux/crypto.h:647
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a8fd)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff81435b4d)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff81435d3d)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8143715e)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81437d7d)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8143ce26)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c061e)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff8124f682)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keyinfo.c (ffffffff812fb85e)
Location: include/linux/crypto.h:660
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813d453a)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff8145d64a)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff814686ba)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff814688ca)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8146998e)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8146a6da)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8146fc16)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916af8)
Location: include/linux/crypto.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff81263d72)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keyinfo.c (ffffffff813110ab)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff813eeb01)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff8147aeda)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/ecb.c (ffffffff8148632a)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff8148653a)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8148774e)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81487f3a)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8148d5f6)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819452a8)
Location: include/linux/crypto.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In mm/zswap.c (ffffffff8127ed02)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keyinfo.c (ffffffff8133842b)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff8141add1)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814a8f3a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814b543e)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814baf76)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff8128e742)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffff8134d6c5)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff81434c21)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814c3b9a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814ce68e)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814d3d46)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff812c1032)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81484cb5)
Location: include/linux/crypto.h:647
Inline: True
```
```
In crypto/skcipher.c (ffffffff81522c2a)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8152da8e)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff81533096)
Location: include/linux/crypto.h:647
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff814a22e5)
Location: include/linux/crypto.h:683
Inline: True
```
```
In crypto/skcipher.c (ffffffff8153fb7a)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8154aa5e)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8154ffe6)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff814a8385)
Location: include/linux/crypto.h:679
Inline: True
```
```
In crypto/skcipher.c (ffffffff815480ea)
Location: include/linux/crypto.h:679
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8155307e)
Location: include/linux/crypto.h:679
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff815587e6)
Location: include/linux/crypto.h:679
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff815006a5)
Location: include/linux/crypto.h:653
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a88ca)
Location: include/linux/crypto.h:653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff815b40ae)
Location: include/linux/crypto.h:653
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff815b9a96)
Location: include/linux/crypto.h:653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff81591715)
Location: include/linux/crypto.h:662
Inline: True
```
```
In crypto/skcipher.c (ffffffff8164fc6a)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8165ceee)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff81663066)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff83ecf09d)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
```
In crypto/skcipher.c (ffffffff817090ea)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8171699e)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8171d2b6)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/pstore/platform.c (ffffffff836f412d)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
```
In crypto/skcipher.c (ffffffff8174293a)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8175224e)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff81758b46)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81784c2a)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff8179250a)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_exit_tfm_simple2
```
```
In crypto/xts.c (ffffffff817940ce)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8179aa46)
Location: include/linux/crypto.h:447
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffff80001032af84)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffff80001040e738)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffff80001051ab38)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffff8000105be53c)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffff8000105ca528)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffff8000105d07d8)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (c0541750)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (c05db210)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (c06d4f7c)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (c076c2a4)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (c0778158)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (c077e170)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (c000000000401f60)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (c00000000051bd0c)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (c000000000664764)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (c000000000745d00)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (c0000000007550b8)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (c00000000075cb74)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffe00022a074)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffe0002b77d6)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffe000383b2a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffe00040394c)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffe00040ea82)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffe00041542c)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff81286d22)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffff81345ca5)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff8142d201)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814bc17a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814c6c6e)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814cc326)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff81278b82)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffff81336985)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff8141dc81)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814acb9a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814b768e)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814bcd46)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff81284b32)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffff81343775)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff814293a1)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814b820a)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814c2cfe)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814c83b6)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In mm/zswap.c (ffffffff812947d2)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/crypto/keysetup.c (ffffffff81356a13)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/pstore/platform.c (ffffffff81440261)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
```
In crypto/skcipher.c (ffffffff814d0cea)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/xts.c (ffffffff814db7ce)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814e0e86)
Location: include/linux/crypto.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
</details>
</li>
</ul>

## Differences

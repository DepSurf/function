# Function: <code>crypto_ablkcipher_encrypt</code>

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
In fs/ext4/crypto.c (ffffffff812e4f76)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_page_crypto
```
```
In fs/ext4/crypto_key.c (ffffffff812e58bb)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
```
```
In fs/ext4/crypto_fname.c (ffffffff812e6130)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - fs/ext4/crypto_fname.c:ext4_fname_encrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff81305364)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In crypto/ablkcipher.c (ffffffff8139f71d)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - crypto/ablkcipher.c:skcipher_null_givencrypt
```
```
In crypto/chainiv.c (ffffffff813a1f66)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - crypto/chainiv.c:chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_givencrypt_tail
```
```
In crypto/eseqiv.c (ffffffff813a27ed)
Location: include/linux/crypto.h:899
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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

# Function: <code>ror32</code>

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
In crypto/sha256_generic.c (0)
Location: include/linux/bitops.h:118
Inline: True
```
```
In crypto/aes_generic.c (ffffffff813a9947)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/sha1.c (ffffffff813f059e)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In crypto/sha256_generic.c (ffffffff813e34f8)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff813e921b)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/sha1.c (ffffffff81436f4e)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
```
```
In lib/iov_iter.c (ffffffff8144429f)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8176d8e2)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff81775068)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:118
Inline: True
```
```
In net/core/filter.c (ffffffff8179ca61)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff817c86c1)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d6a7e)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817e5810)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff817f1cda)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff817fb37d)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:118
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8185364a)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81855562)
Location: include/linux/bitops.h:118
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:118
Inline: True
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
In crypto/sha256_generic.c (ffffffff813fc518)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff8140284b)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/sha1.c (ffffffff81453f3e)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
```
```
In lib/iov_iter.c (ffffffff81462493)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8179ad3c)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff817a235d)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/core/filter.c (ffffffff817ca271)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff817f8251)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81806b44)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81815c84)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff81822afa)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8182c22d)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8188535a)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff818872d2)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:108
Inline: True
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
In crypto/sha256_generic.c (ffffffff81409808)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff8140fbd6)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/iov_iter.c (ffffffff81468189)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff817b8157)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff817bfbee)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/core/filter.c (ffffffff817e9205)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff81818651)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818270f2)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff8183602e)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff818437ce)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8184d6ed)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818ab79e)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff818ad882)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:108
Inline: True
```
```
In lib/sha1.c (ffffffff818f406e)
Location: include/linux/bitops.h:108
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In crypto/sha256_generic.c (ffffffff81432228)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff8143a5be)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/iov_iter.c (ffffffff8149441f)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81830bb1)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff8183979e)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/core/filter.c (ffffffff8186460d)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff818977b1)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a530b)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff818b55ee)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff818c31ae)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff818cd42d)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192e33e)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81930512)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In lib/sha1.c (ffffffff8197aa6e)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In crypto/sha256_generic.c (ffffffff81464d8f)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff8146d02d)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/iov_iter.c (ffffffff814c99a3)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8187b09f)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff81883ecd)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/core/filter.c (ffffffff818b6a0b)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff818ee598)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818fae29)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8192380d)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff819891a2)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:110
Inline: True
```
```
In lib/sha1.c (ffffffff819d6ffb)
Location: include/linux/bitops.h:110
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In crypto/sha256_generic.c (ffffffff814829ff)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff8148a9dd)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/iov_iter.c (ffffffff814dea0b)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8189ba39)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/core/filter.c (ffffffff818dbe57)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff8191bd59)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81928d91)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819525fd)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff819bfad2)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In lib/sha1.c (ffffffff81a0f23b)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In crypto/sha256_generic.c (ffffffff814b0c2c)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/aes_generic.c (ffffffff814b80ae)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
  - crypto/aes_generic.c:crypto_aes_expand_key
```
```
In lib/iov_iter.c (ffffffff8150a3f2)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff818e6302)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/core/filter.c (ffffffff81929053)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8197af81)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198bd16)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819b6ebd)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81a2e772)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:91
Inline: True
```
```
In lib/sha1.c (ffffffff81a7e7b2)
Location: include/linux/bitops.h:91
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff8152852c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff8152ed6a)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff8152f777)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff81918461)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8195b733)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b18f1)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c25fb)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819edbbd)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81a652c2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffff81ab59b2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff815883b9)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
```
```
In lib/crypto/aes.c (ffffffff81593510)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff81593a6a)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/sha1.c (ffffffff815f047f)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In net/core/skbuff.c (ffffffff819eac14)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/core/filter.c (ffffffff81a2fd68)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a9b9d1)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81aac624)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81adb9bd)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81b5dc22)
Location: include/linux/bitops.h:113
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:113
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:113
Inline: True
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
In lib/iov_iter.c (ffffffff815a806d)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
```
```
In lib/crypto/aes.c (ffffffff815b0125)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff815b09a4)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/sha1.c (ffffffff81614bdf)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In net/core/skbuff.c (ffffffff819ea954)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/core/filter.c (ffffffff81a32638)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81aa582f)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ab3f74)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81ae848a)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81b6c3ef)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:116
Inline: True
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
In lib/iov_iter.c (ffffffff815b34f8)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff815baf46)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff815bb79a)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/sha1.c (ffffffff815f8270)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In net/core/skbuff.c (ffffffff819d0fcf)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/core/filter.c (ffffffff81a1979a)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a908ef)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81a9f0e4)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81ad371a)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81b5a73f)
Location: include/linux/bitops.h:116
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:116
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:116
Inline: True
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
In lib/iov_iter.c (ffffffff8161982e)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff81621b26)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff81622331)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/sha1.c (ffffffff81665b10)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In net/core/skbuff.c (ffffffff81a80a0f)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/core/filter.c (ffffffff81acaa3a)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81b4b96f)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a234)
Location: include/linux/bitops.h:117
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81b9236a)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81c2200f)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/bitops.h:117
Inline: False
```
```
In net/mptcp/protocol.c (ffffffff81c77917)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c80990)
Location: include/linux/bitops.h:117
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff816e685e)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff816efd86)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/blake2s-generic.c (ffffffff816f0623)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
```
```
In lib/crypto/sha256.c (ffffffff816f1f90)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/sha1.c (ffffffff8178019b)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8178e74c)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
```
```
In net/core/skbuff.c (ffffffff81bf5405)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81c483ca)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81cd902f)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8586)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81d23c7a)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81dbecef)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/bitops.h:83
Inline: False
```
```
In net/mptcp/protocol.c (ffffffff81e1cb87)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e25bb2)
Location: include/linux/bitops.h:83
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff817d639b)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff817e0bb6)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/blake2s-generic.c (ffffffff817e2133)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
```
```
In lib/crypto/sha1.c (ffffffff817e37c0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff817e3d70)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff81da3935)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81dfd35a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81e9963f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabed6)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81eeb20a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f0bae6)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81f8f27f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/mptcp/protocol.c (ffffffff81ff4017)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffd842)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8204c028)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In lib/iov_iter.c (ffffffff81813c6c)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff8182031a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/blake2s-generic.c (ffffffff81822091)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
```
```
In lib/crypto/sha1.c (ffffffff81823710)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff81823cc0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff81e14cd8)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81e7326b)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81ef7f3f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a696)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81f4ab2a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f6b6b6)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81fefa7f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/mptcp/protocol.c (ffffffff82070627)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079b12)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff820ca8cb)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In lib/crypto/aes.c (ffffffff8186629a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/blake2s-generic.c (ffffffff818680d1)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
  - lib/crypto/blake2s-generic.c:blake2s_compress_generic
```
```
In lib/crypto/sha1.c (ffffffff81869750)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff81869d00)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff81ece5a7)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/datagram.c (ffffffff81edd67e)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/core/filter.c (ffffffff81f329eb)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81fbbf8f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81fce695)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff82010c3a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff8203171a)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff820bd64f)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/bitops.h:134
Inline: False
```
```
In net/mptcp/protocol.c (ffffffff82144587)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214ef72)
Location: include/linux/bitops.h:134
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffff800010632bd4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffff80001063b4d4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffff80001063bb3c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffff800010bb1788)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffff800010bfc978)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffff800010c96658)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffff800010ca36e4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d28188)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffff800010d2b284)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffff800010d90250)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In arch/arm/net/bpf_jit_32.c (c03292a8)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:build_prologue
  - arch/arm/net/bpf_jit_32.c:emit_str_r
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
  - arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64
```
```
In lib/iov_iter.c (c07d8d24)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (c07e17c8)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (c07e1f48)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/irqchip/irq-gic.c (c0815cd4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_migrate_target
```
```
In net/core/skbuff.c (c0ccf284)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (c0d1799c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (c0d71820)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c0d839d0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c0da4cbc)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (c0db03d4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (c0e2cbec)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (c0e2f0fc)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (c0e8a9bc)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (c0000000007d608c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_memcpy
```
```
In lib/crypto/aes.c (c0000000007e2850)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (c0000000007e3134)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (c000000000c88cc8)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (c000000000ce8cbc)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (c000000000d65938)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7c904)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c000000000da8050)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (c000000000db6ed4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (c000000000e59410)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (c000000000e5c60c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (c000000000ed35d8)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffe00046105c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffe000467e90)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffe000468940)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffe0007430fa)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffe00077f670)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffe0007ca318)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d8606)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffe0007f57e6)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffe0007ff580)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086995a)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffe00086b6c4)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffe0008b85ea)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff81520b0c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff8152734a)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff81527d57)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff818b8461)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff818fb703)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81951761)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8196246b)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8198d95d)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81a04952)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffff81a54802)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff81510dfc)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff8151762a)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff81518037)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/net/vxlan.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/skbuff.c (ffffffff818723b1)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff818b5533)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190b251)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191bf5b)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8194741d)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ip_tunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff819c1712)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffff81a118e2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff8151cb9c)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff815233da)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff81523de7)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff81909461)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8194c733)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bbf31)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819ccc3b)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819f81fd)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81a6f3d2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffff81ac0bf2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
In lib/iov_iter.c (ffffffff815363f7)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In lib/crypto/aes.c (ffffffff8153cd5a)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_expandkey
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
  - lib/crypto/aes.c:inv_mix_columns
```
```
In lib/crypto/sha256.c (ffffffff8153d767)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In net/core/skbuff.c (ffffffff8192a541)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8196e0f3)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c5841)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d67cb)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81a024fd)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81a7ba02)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/bitops.h:98
Inline: True
```
```
In lib/sha1.c (ffffffff81acd0c2)
Location: include/linux/bitops.h:98
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
```
</details>
</li>
</ul>

## Differences

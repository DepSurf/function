# Function: <code>crypto_skcipher_ivsize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:274
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
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:274
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f6aa0)
Location: include/crypto/skcipher.h:274
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:278
Inline: True
```
```
In crypto/skcipher.c (ffffffff81402e7d)
Location: include/crypto/skcipher.h:278
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:278
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142b4ec)
Location: include/crypto/skcipher.h:278
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff82715d4f)
Location: include/crypto/skcipher.h:278
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8145e208)
Location: include/crypto/skcipher.h:278
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828cd191)
Location: include/crypto/skcipher.h:285
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8147baa8)
Location: include/crypto/skcipher.h:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828e6bcd)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814a9e48)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828ef6b8)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814c4b38)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In fs/crypto/keysetup.c (ffffffff81393465)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82d048c5)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81523ca9)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff813a4605)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82ff1c92)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81540bf9)
Location: include/crypto/skcipher.h:249
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff813ab9ca)
Location: include/crypto/skcipher.h:251
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff831fc61c)
Location: include/crypto/skcipher.h:251
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81549259)
Location: include/crypto/skcipher.h:251
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff813fb279)
Location: include/crypto/skcipher.h:251
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff832e366e)
Location: include/crypto/skcipher.h:251
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff815a9a39)
Location: include/crypto/skcipher.h:251
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff8146e5a7)
Location: include/crypto/skcipher.h:255
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83499a7f)
Location: include/crypto/skcipher.h:255
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81650edd)
Location: include/crypto/skcipher.h:255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff814ffbf7)
Location: include/crypto/skcipher.h:255
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83ecfbad)
Location: include/crypto/skcipher.h:255
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8170a6fd)
Location: include/crypto/skcipher.h:255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff815371c7)
Location: include/crypto/skcipher.h:277
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff836f4c6b)
Location: include/crypto/skcipher.h:277
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81743f4d)
Location: include/crypto/skcipher.h:277
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
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
In fs/crypto/keysetup.c (ffffffff8156c297)
Location: include/crypto/skcipher.h:420
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83927e6b)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81785420)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_import
  - crypto/skcipher.c:crypto_skcipher_export
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffff8000114693a0)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffff8000105bf594)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (c1541ee0)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c076d2f4)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (c000000001397510)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c0000000007472e8)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffe0000245fe)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffe00040473c)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828d856c)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814bd118)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828d0c88)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814adb38)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828eb2ec)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814b91a8)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
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
In security/keys/encrypted-keys/encrypted.c (ffffffff828f0702)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814d1c68)
Location: include/crypto/skcipher.h:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
</details>
</li>
</ul>

## Differences

# Function: <code>sha256_init</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814cb7b5)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
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
In crypto/sha256_generic.c (ffffffff8152ac25)
Location: include/crypto/sha.h:136
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
```
In drivers/firmware/efi/embedded-firmware.c (ffffffff82d2b894)
Location: include/crypto/sha.h:136
Inline: True
Inline callers:
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
```
```
In net/mptcp/crypto.c (ffffffff81bb1f43)
Location: include/crypto/sha.h:136
Inline: True
Inline callers:
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_key_sha
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
In crypto/sha256_generic.c (ffffffff81547bf5)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
```
In lib/crypto/sha256.c (0)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff815502b5)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
```
In lib/crypto/sha256.c (0)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff815b0c35)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
```
In lib/crypto/sha256.c (0)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff81659680)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_base_init
```
```
In lib/crypto/sha256.c (ffffffff816f27fe)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff81713970)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_base_init
```
```
In lib/crypto/sha256.c (ffffffff817e460e)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff8174e780)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_base_init
```
```
In lib/crypto/sha256.c (ffffffff81824780)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
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
In crypto/sha256_generic.c (ffffffff817903d0)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_base_init
```
```
In lib/crypto/sha256.c (ffffffff8186a7c0)
Location: include/crypto/sha2.h:103
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffff8000105c76f8)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (c0774180)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (c0000000007512d8)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffe00040b6ca)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814c3d95)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814b47b5)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814bfe25)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814d88f5)
Location: include/crypto/sha.h:126
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_init
```
</details>
</li>
</ul>

## Differences

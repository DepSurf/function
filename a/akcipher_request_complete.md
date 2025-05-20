# Function: <code>akcipher_request_complete</code>

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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff8170f84d)
Location: include/crypto/internal/akcipher.h:69
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff81749fc9)
Location: include/crypto/internal/akcipher.h:69
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff8178be69)
Location: include/crypto/internal/akcipher.h:69
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
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

# Function: <code>crypto_kpp_tfm</code>

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
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (ffffffff814a02f3)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
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
In security/keys/dh.c (ffffffff814bdd03)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
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
In security/keys/dh.c (ffffffff814c3b73)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
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
In security/keys/dh.c (ffffffff8151c543)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (ffffffff815af60b)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/dh.c (ffffffff81653a82)
Location: include/crypto/kpp.h:107
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_exit_tfm
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
In security/keys/dh.c (ffffffff81659e2b)
Location: include/crypto/kpp.h:110
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:110
Inline: True
```
```
In crypto/dh.c (ffffffff8170dd5f)
Location: include/crypto/kpp.h:110
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_exit_tfm
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
In security/keys/dh.c (ffffffff81692621)
Location: include/crypto/kpp.h:133
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:133
Inline: True
```
```
In crypto/dh.c (ffffffff8174893a)
Location: include/crypto/kpp.h:133
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_exit_tfm
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
In security/keys/dh.c (ffffffff816cebf1)
Location: include/crypto/kpp.h:133
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:133
Inline: True
```
```
In crypto/dh.c (ffffffff8178a88a)
Location: include/crypto/kpp.h:133
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_exit_tfm
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:107
Inline: True
```
</details>
</li>
</ul>

## Differences

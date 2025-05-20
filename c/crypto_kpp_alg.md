# Function: <code>crypto_kpp_alg</code>

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
In crypto/kpp.c (ffffffff813e0365)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
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
In crypto/kpp.c (ffffffff813f88e5)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
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
In security/keys/dh.c (ffffffff813960dc)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81404dd5)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
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
In security/keys/dh.c (ffffffff813bb858)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8142d6e5)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
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
In security/keys/dh.c (ffffffff813ec574)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81460365)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff81407116)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8147ddb5)
Location: include/crypto/kpp.h:127
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff81434278)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814ac0d5)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff8144dfc8)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814c6d85)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff814a022b)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81526035)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff814bdc3b)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81542f95)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff814c3aab)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8154b635)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff8151c47b)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff815abe15)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff815af53e)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81653795)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
```
In crypto/dh.c (ffffffff81653a1a)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_max_size
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
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
In security/keys/dh.c (ffffffff81659d4c)
Location: include/crypto/kpp.h:125
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8170d615)
Location: include/crypto/kpp.h:125
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
```
In crypto/dh.c (ffffffff8170d98a)
Location: include/crypto/kpp.h:125
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_max_size
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
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
In security/keys/dh.c (ffffffff816925b7)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81747d85)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
```
In crypto/dh.c (ffffffff817481fa)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_max_size
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
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
In security/keys/dh.c (ffffffff816ceb87)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81789bf5)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
```
In crypto/dh.c (ffffffff8178a06a)
Location: include/crypto/kpp.h:148
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_max_size
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
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
In security/keys/dh.c (ffff800010538848)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffff8000105c23d0)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (c06ef20c)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (c076f84c)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (c000000000687404)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (c00000000074ab50)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffe000397518)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffe000406e4e)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff814465a8)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814bf365)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff81436ff8)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814afd85)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff81442648)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814bb3f5)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
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
In security/keys/dh.c (ffffffff81459978)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814d3ec5)
Location: include/crypto/kpp.h:122
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
</details>
</li>
</ul>

## Differences

# Function: <code>crypto_kpp_reqtfm</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:143
Inline: True
```
```
In crypto/dh.c (ffffffff81404f77)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
Location: include/crypto/kpp.h:143
Inline: True
```
```
In crypto/dh.c (ffffffff8142d8f7)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff813ec683)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8146058c)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff81407249)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8147e0ee)
Location: include/crypto/kpp.h:143
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff814343a7)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814ac40e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff8144e0f7)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814c70be)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff814a036a)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8152632e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff814bdd7a)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff815432ce)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff814c3bea)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8154b89e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff8151c5ba)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff815ac07e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff815af67b)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff81653a65)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff81659e95)
Location: include/crypto/kpp.h:141
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8170dd45)
Location: include/crypto/kpp.h:141
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:164
Inline: True
```
```
In crypto/dh.c (ffffffff81748925)
Location: include/crypto/kpp.h:164
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:164
Inline: True
```
```
In crypto/dh.c (ffffffff8178a875)
Location: include/crypto/kpp.h:164
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffff800010538930)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffff8000105c27c0)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (c06ef314)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (c076faac)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (c000000000687530)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (c00000000074b080)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffe0003975fe)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffe0004071ae)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff814466d7)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814bf69e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff81437127)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814b00be)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff81442777)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814bb72e)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In security/keys/dh.c (ffffffff81459aa7)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff814d41fe)
Location: include/crypto/kpp.h:138
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
```
</details>
</li>
</ul>

## Differences

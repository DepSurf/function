# Function: <code>__crypto_kpp_alg</code>

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
Location: include/crypto/kpp.h:117
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
Location: include/crypto/kpp.h:117
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
Location: include/crypto/kpp.h:117
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:117
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
Location: include/crypto/kpp.h:117
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:117
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
In security/keys/dh.c (ffffffff813ec574)
Location: include/crypto/kpp.h:117
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81460369)
Location: include/crypto/kpp.h:117
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
In security/keys/dh.c (ffffffff8140711a)
Location: include/crypto/kpp.h:117
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8147ddb9)
Location: include/crypto/kpp.h:117
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
In security/keys/dh.c (ffffffff8143427c)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814ac0d9)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff8144dfcc)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814c6d89)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff814a022f)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81526039)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff814bdc3f)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff81542f99)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff814c3aaf)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff8154b639)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff8151c47f)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff815abe19)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:112
Inline: True
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:112
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:115
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:115
Inline: True
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:115
Inline: True
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
Location: include/crypto/kpp.h:138
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:138
Inline: True
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:138
Inline: True
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
Location: include/crypto/kpp.h:138
Inline: True
```
```
In crypto/kpp.c (0)
Location: include/crypto/kpp.h:138
Inline: True
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:138
Inline: True
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
In security/keys/dh.c (ffff80001053884c)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffff8000105c23d4)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (c06ef210)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (c076f850)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (c00000000068740c)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (c00000000074ab54)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffe00039751a)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffe000406e50)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff814465ac)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814bf369)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff81436ffc)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814afd89)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff8144264c)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814bb3f9)
Location: include/crypto/kpp.h:112
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
In security/keys/dh.c (ffffffff8145997c)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/kpp.c (ffffffff814d3ec9)
Location: include/crypto/kpp.h:112
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_init_tfm
  - crypto/kpp.c:crypto_kpp_exit_tfm
```
</details>
</li>
</ul>

## Differences

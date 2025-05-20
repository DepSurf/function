# Function: <code>kpp_request_set_tfm</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8139608b)
Location: include/crypto/kpp.h:137
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813bb811)
Location: include/crypto/kpp.h:137
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813ec615)
Location: include/crypto/kpp.h:137
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814071d7)
Location: include/crypto/kpp.h:137
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81434339)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8144e089)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814a02f3)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814bdd03)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814c3b73)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8151c543)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff81653a82)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
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
Location: include/crypto/kpp.h:135
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8170dd5f)
Location: include/crypto/kpp.h:135
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
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
In security/keys/dh.c (ffffffff816927d4)
Location: include/crypto/kpp.h:158
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8174893a)
Location: include/crypto/kpp.h:158
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
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
In security/keys/dh.c (ffffffff816ceda4)
Location: include/crypto/kpp.h:158
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8178a88a)
Location: include/crypto/kpp.h:158
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
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
In security/keys/dh.c (ffff8000105388e4)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (c06ef2c0)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (c0000000006874cc)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffe0003975a6)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff81446669)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff814370b9)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff81442709)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff81459a39)
Location: include/crypto/kpp.h:132
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
</ul>

## Differences

# Function: <code>crypto_free_kpp</code>

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
In security/keys/dh.c (ffffffff8139618f)
Location: include/crypto/kpp.h:153
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
In security/keys/dh.c (ffffffff813bb911)
Location: include/crypto/kpp.h:163
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
In security/keys/dh.c (ffffffff813ec8fe)
Location: include/crypto/kpp.h:163
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
In security/keys/dh.c (ffffffff814074f4)
Location: include/crypto/kpp.h:163
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
In security/keys/dh.c (ffffffff81434654)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff8144e3b4)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff814a047d)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff814bde8d)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff814c3cf7)
Location: include/crypto/kpp.h:160
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
In security/keys/dh.c (ffffffff8151c6c7)
Location: include/crypto/kpp.h:160
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
In security/keys/dh.c (ffffffff815af79d)
Location: include/crypto/kpp.h:160
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff81653a4a)
Location: include/crypto/kpp.h:160
Inline: True
Inline callers:
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
In security/keys/dh.c (ffffffff81659fb7)
Location: include/crypto/kpp.h:163
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8170dcca)
Location: include/crypto/kpp.h:163
Inline: True
Inline callers:
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
Location: include/crypto/kpp.h:186
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8174853a)
Location: include/crypto/kpp.h:186
Inline: True
Inline callers:
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
Location: include/crypto/kpp.h:186
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8178a3aa)
Location: include/crypto/kpp.h:186
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_exit_tfm
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
In security/keys/dh.c (ffff8000105389ec)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (c06ef438)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (c000000000687748)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffe0003976ae)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff81446994)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff814373e4)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff81442a34)
Location: include/crypto/kpp.h:158
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
In security/keys/dh.c (ffffffff81459d64)
Location: include/crypto/kpp.h:158
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
</ul>

## Differences

# Function: <code>crypto_kpp_set_secret</code>

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
In security/keys/dh.c (ffffffff81395fe2)
Location: include/crypto/kpp.h:276
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
In security/keys/dh.c (ffffffff813bb764)
Location: include/crypto/kpp.h:286
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
In security/keys/dh.c (ffffffff813ec574)
Location: include/crypto/kpp.h:286
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
In security/keys/dh.c (ffffffff81407116)
Location: include/crypto/kpp.h:286
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
In security/keys/dh.c (ffffffff81434278)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff8144dfc8)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff814a022b)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff814bdc3b)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff814c3aab)
Location: include/crypto/kpp.h:283
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
In security/keys/dh.c (ffffffff8151c47b)
Location: include/crypto/kpp.h:283
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
In security/keys/dh.c (ffffffff815af53e)
Location: include/crypto/kpp.h:283
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff816544f7)
Location: include/crypto/kpp.h:283
Inline: True
Inline callers:
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
Location: include/crypto/kpp.h:286
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8170e4d7)
Location: include/crypto/kpp.h:286
Inline: True
Inline callers:
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
Location: include/crypto/kpp.h:329
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff81748e18)
Location: include/crypto/kpp.h:329
Inline: True
Inline callers:
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
Location: include/crypto/kpp.h:329
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (ffffffff8178acb8)
Location: include/crypto/kpp.h:329
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_set_secret
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
In security/keys/dh.c (ffff800010538848)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (c06ef20c)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (c000000000687404)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffe000397518)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff814465a8)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff81436ff8)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff81442648)
Location: include/crypto/kpp.h:281
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
In security/keys/dh.c (ffffffff81459978)
Location: include/crypto/kpp.h:281
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
</ul>

## Differences

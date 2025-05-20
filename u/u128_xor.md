# Function: <code>u128_xor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gf128mul.c (ffffffff813e677c)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_64k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_lle
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff813e8251)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:crypt
  - crypto/xts.c:crypt
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
In crypto/gf128mul.c (ffffffff813ff74c)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81400fd1)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/gf128mul.c (ffffffff8140c596)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8140e307)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/gf128mul.c (ffffffff81434ff6)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81436dbc)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/gf128mul.c (ffffffff81467b99)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8146a18c)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/gf128mul.c (ffffffff81485809)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8148766f)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814b3a15)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814b5360)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814cc785)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814ce41f)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff8152c31b)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8152d74d)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff8154930b)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8154a6e1)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff815519f8)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81552d05)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff815b2a02)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff815b3d35)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff8165b518)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8165cb28)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81716568)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
```
```
In lib/crypto/gf128mul.c (ffffffff817e1b28)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/gf128mul.c (ffff8000105c89f0)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffff8000105ca2f8)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (c0775d84)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (c0777ef0)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (c0000000007525d4)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (c000000000754de4)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffe00040d08a)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffe00040e8a8)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814c4d65)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814c69ff)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814b5785)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814b741f)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814c0df5)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814c2a8f)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814d98c5)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814db55f)
Location: include/crypto/b128ops.h:64
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
```
</details>
</li>
</ul>

## Differences

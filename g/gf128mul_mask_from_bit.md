# Function: <code>gf128mul_mask_from_bit</code>

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
In crypto/gf128mul.c (ffffffff8140ce29)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8140e44c)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
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
In crypto/gf128mul.c (ffffffff81435889)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81436f06)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
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
In crypto/gf128mul.c (ffffffff814682ea)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8146a1be)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
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
In crypto/gf128mul.c (ffffffff8148607a)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8148768b)
Location: include/crypto/gf128mul.h:176
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
In crypto/gf128mul.c (ffffffff814b428a)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814b5380)
Location: include/crypto/gf128mul.h:176
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
In crypto/gf128mul.c (ffffffff814ccffa)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814ce1b1)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff8152beb4)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8152d4e3)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff81548fc4)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8154a533)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff81551694)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81552b61)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff815b26d4)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff815b3b91)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
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
In crypto/gf128mul.c (ffffffff8165b400)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff8165c939)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81716369)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
```
```
In lib/crypto/gf128mul.c (ffffffff817e1a00)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In crypto/xts.c (ffffffff81751c5a)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
```
```
In lib/crypto/gf128mul.c (ffffffff818212c0)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In crypto/xts.c (ffffffff81793ada)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
```
```
In lib/crypto/gf128mul.c (ffffffff8186700f)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffff8000105c86e4)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffff8000105ca0c0)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (c077681c)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (c0777c08)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (c000000000753250)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (c000000000754ad8)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffe00040caac)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffe00040e6be)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814c55da)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814c6791)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814b5ffa)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814b71b1)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814c166a)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814c2821)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/gf128mul.c (ffffffff814da13a)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff814db2f1)
Location: include/crypto/gf128mul.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
```
</details>
</li>
</ul>

## Differences

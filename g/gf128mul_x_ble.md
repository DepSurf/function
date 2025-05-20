# Function: <code>gf128mul_x_ble</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gf128mul_x_ble(be128 *r, const be128 *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gf128mul.c (ffffffff813e6100)
Location: crypto/gf128mul.c:145
Inline: False
Direct callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:crypt
```
**Symbols:**

```
ffffffff813e6100-ffffffff813e6139: gf128mul_x_ble (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gf128mul_x_ble(be128 *r, const be128 *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gf128mul.c (ffffffff813ff120)
Location: crypto/gf128mul.c:145
Inline: False
Direct callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
```
**Symbols:**

```
ffffffff813ff120-ffffffff813ff159: gf128mul_x_ble (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140e426)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
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
In crypto/xts.c (ffffffff81436ee0)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
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
In crypto/xts.c (ffffffff8146a1be)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
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
In crypto/xts.c (ffffffff8148768b)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814b5380)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814ce1b1)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152d4e3)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8154a533)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81552b61)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff815b3b91)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8165c939)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81716369)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81751c5a)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81793ada)
Location: include/crypto/gf128mul.h:208
Inline: True
Inline callers:
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffff8000105ca0c0)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0777c08)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c000000000754ad8)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040e6b2)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c6791)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b71b1)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c2821)
Location: include/crypto/gf128mul.h:208
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db2f1)
Location: include/crypto/gf128mul.h:208
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>

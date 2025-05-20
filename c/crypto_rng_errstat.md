# Function: <code>crypto_rng_errstat</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff817421c7)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff81748b5d)
Location: include/crypto/rng.h:156
Inline: True
```
```
In crypto/rng.c (ffffffff817584ce)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff817593e3)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff817830a7)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff8178a9fd)
Location: include/crypto/rng.h:156
Inline: True
```
```
In crypto/rng.c (ffffffff8179a3ce)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8179b2e3)
Location: include/crypto/rng.h:156
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

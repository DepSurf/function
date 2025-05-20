# Function: <code>blk_crypto_keyslot_index</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_crypto_keyslot_index(struct blk_crypto_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c2b28)
Location: block/blk-crypto-profile.c:218
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff816c1dd0-ffffffff816c1df6: blk_crypto_keyslot_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_crypto_keyslot_index(struct blk_crypto_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783eb8)
Location: block/blk-crypto-profile.c:219
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff81783050-ffffffff81783076: blk_crypto_keyslot_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_crypto_keyslot_index(struct blk_crypto_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c419c)
Location: block/blk-crypto-profile.c:226
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff817c3310-ffffffff817c3336: blk_crypto_keyslot_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_crypto_keyslot_index(struct blk_crypto_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808e2c)
Location: block/blk-crypto-profile.c:226
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff81807fa0-ffffffff81807fc6: blk_crypto_keyslot_index (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

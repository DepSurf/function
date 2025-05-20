# Function: <code>blk_crypto_profile_destroy</code>

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
void blk_crypto_profile_destroy(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c2269)
Location: block/blk-crypto-profile.c:443
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff816c2470-ffffffff816c24f9: blk_crypto_profile_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783569)
Location: block/blk-crypto-profile.c:444
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff817837b0-ffffffff81783839: blk_crypto_profile_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c38a4)
Location: block/blk-crypto-profile.c:441
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
Direct callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff817c3660-ffffffff817c36d7: blk_crypto_profile_destroy.part.0 (STB_LOCAL)
ffffffff817c3aa0-ffffffff817c3b29: blk_crypto_profile_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808534)
Location: block/blk-crypto-profile.c:441
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
Direct callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818082f0-ffffffff81808367: blk_crypto_profile_destroy.part.0 (STB_LOCAL)
ffffffff81808730-ffffffff818087b9: blk_crypto_profile_destroy (STB_GLOBAL)
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

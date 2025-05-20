# Function: <code>blk_crypto_profile_init</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_crypto_profile_init(struct blk_crypto_profile *profile, unsigned int num_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:73
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff81e8e1f7-ffffffff81e8e215: blk_crypto_profile_init.cold (STB_LOCAL)
ffffffff816c20a0-ffffffff816c22c7: blk_crypto_profile_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blk_crypto_profile_init(struct blk_crypto_profile *profile, unsigned int num_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:74
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff8207740e-ffffffff8207742c: blk_crypto_profile_init.cold (STB_LOCAL)
ffffffff817833a0-ffffffff817835c7: blk_crypto_profile_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blk_crypto_profile_init(struct blk_crypto_profile *profile, unsigned int num_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:74
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff820f746f-ffffffff820f748d: blk_crypto_profile_init.cold (STB_LOCAL)
ffffffff817c36f0-ffffffff817c38bb: blk_crypto_profile_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_crypto_profile_init(struct blk_crypto_profile *profile, unsigned int num_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:74
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff821d4e97-ffffffff821d4eb5: blk_crypto_profile_init.cold (STB_LOCAL)
ffffffff81808380-ffffffff8180854b: blk_crypto_profile_init (STB_GLOBAL)
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

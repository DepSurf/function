# Function: <code>blk_crypto_register</code>

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
bool blk_crypto_register(struct blk_crypto_profile *profile, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:454
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff81e8e1db-ffffffff81e8e1f7: blk_crypto_register.cold (STB_LOCAL)
ffffffff816c1fa0-ffffffff816c1fc8: blk_crypto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_crypto_register(struct blk_crypto_profile *profile, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783250)
Location: block/blk-crypto-profile.c:455
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff81783250-ffffffff81783290: blk_crypto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_crypto_register(struct blk_crypto_profile *profile, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c3500)
Location: block/blk-crypto-profile.c:453
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff817c3500-ffffffff817c3540: blk_crypto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_crypto_register(struct blk_crypto_profile *profile, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808190)
Location: block/blk-crypto-profile.c:453
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff81808190-ffffffff818081d0: blk_crypto_register (STB_GLOBAL)
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

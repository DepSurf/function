# Function: <code>blk_crypto_has_capabilities</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_crypto_has_capabilities(const struct blk_crypto_profile *target, const struct blk_crypto_profile *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c1e00)
Location: block/blk-crypto-profile.c:505
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff816c1e00-ffffffff816c1eb1: blk_crypto_has_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_crypto_has_capabilities(const struct blk_crypto_profile *target, const struct blk_crypto_profile *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783090)
Location: block/blk-crypto-profile.c:506
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff81783090-ffffffff81783141: blk_crypto_has_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_crypto_has_capabilities(const struct blk_crypto_profile *target, const struct blk_crypto_profile *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c3350)
Location: block/blk-crypto-profile.c:504
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff817c3350-ffffffff817c3401: blk_crypto_has_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_crypto_has_capabilities(const struct blk_crypto_profile *target, const struct blk_crypto_profile *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81807fe0)
Location: block/blk-crypto-profile.c:504
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
```
**Symbols:**

```
ffffffff81807fe0-ffffffff81808091: blk_crypto_has_capabilities (STB_GLOBAL)
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

# Function: <code>blk_crypto_intersect_capabilities</code>

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
void blk_crypto_intersect_capabilities(struct blk_crypto_profile *parent, const struct blk_crypto_profile *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c1ec0)
Location: block/blk-crypto-profile.c:478
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
```
**Symbols:**

```
ffffffff816c1ec0-ffffffff816c1f96: blk_crypto_intersect_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_crypto_intersect_capabilities(struct blk_crypto_profile *parent, const struct blk_crypto_profile *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783160)
Location: block/blk-crypto-profile.c:479
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
```
**Symbols:**

```
ffffffff81783160-ffffffff8178323d: blk_crypto_intersect_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_crypto_intersect_capabilities(struct blk_crypto_profile *parent, const struct blk_crypto_profile *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c3420)
Location: block/blk-crypto-profile.c:477
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
```
**Symbols:**

```
ffffffff817c3420-ffffffff817c34e4: blk_crypto_intersect_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_crypto_intersect_capabilities(struct blk_crypto_profile *parent, const struct blk_crypto_profile *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff818080b0)
Location: block/blk-crypto-profile.c:477
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
```
**Symbols:**

```
ffffffff818080b0-ffffffff81808174: blk_crypto_intersect_capabilities (STB_GLOBAL)
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

# Function: <code>dm_keyslot_evict</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81964400)
Location: drivers/md/dm-table.c:1221
Inline: False
```
**Symbols:**

```
ffffffff81964400-ffffffff819644c6: dm_keyslot_evict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c3b0)
Location: drivers/md/dm-table.c:1216
Inline: False
```
**Symbols:**

```
ffffffff81a0c3b0-ffffffff81a0c476: dm_keyslot_evict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b74bf0)
Location: drivers/md/dm-table.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81b74bf0-ffffffff81b74cc3: dm_keyslot_evict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11c40)
Location: drivers/md/dm-table.c:1229
Inline: False
```
**Symbols:**

```
ffffffff81d11c40-ffffffff81d11d13: dm_keyslot_evict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b020)
Location: drivers/md/dm-table.c:1213
Inline: False
```
**Symbols:**

```
ffffffff81d7b020-ffffffff81d7b0e9: dm_keyslot_evict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_keyslot_evict(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e31fa0)
Location: drivers/md/dm-table.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81e31fa0-ffffffff81e32069: dm_keyslot_evict (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_crypto_profile *profile</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_keyslot_manager *ksm</code>
</li>
</ul>
</details>
</li>
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

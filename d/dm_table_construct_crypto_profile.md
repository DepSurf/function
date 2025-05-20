# Function: <code>dm_table_construct_crypto_profile</code>

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
int dm_table_construct_crypto_profile(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1276
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81b756b0-ffffffff81b75802: dm_table_construct_crypto_profile (STB_LOCAL)
ffffffff81ef630b-ffffffff81ef6329: dm_table_construct_crypto_profile.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_table_construct_crypto_profile(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d129b0)
Location: drivers/md/dm-table.c:1294
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d129b0-ffffffff81d12b29: dm_table_construct_crypto_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_table_construct_crypto_profile(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7bd70)
Location: drivers/md/dm-table.c:1278
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d7bd70-ffffffff81d7bee8: dm_table_construct_crypto_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_table_construct_crypto_profile(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e33010)
Location: drivers/md/dm-table.c:1300
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81e33010-ffffffff81e331b7: dm_table_construct_crypto_profile (STB_LOCAL)
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

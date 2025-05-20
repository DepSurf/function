# Function: <code>dm_split_and_process_bio</code>

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
void dm_split_and_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1663
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff81b72860-ffffffff81b72d03: dm_split_and_process_bio (STB_LOCAL)
ffffffff81ef624f-ffffffff81ef626a: dm_split_and_process_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dm_split_and_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1730
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff81d0f640-ffffffff81d0fab3: dm_split_and_process_bio (STB_LOCAL)
ffffffff820a860e-ffffffff820a8623: dm_split_and_process_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dm_split_and_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1772
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff81d78a30-ffffffff81d78f31: dm_split_and_process_bio (STB_LOCAL)
ffffffff82129823-ffffffff82129838: dm_split_and_process_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_split_and_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2fc70)
Location: drivers/md/dm.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff81e2fc70-ffffffff81e300ef: dm_split_and_process_bio (STB_LOCAL)
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

# Function: <code>dm_zone_map_bio_end</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device *md, struct bio *orig_bio, unsigned int nr_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:428
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81a05580-ffffffff81a056da: dm_zone_map_bio_end (STB_LOCAL)
ffffffff81d29d48-ffffffff81d29d99: dm_zone_map_bio_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:429
Inline: True
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81b6d260-ffffffff81b6d33f: dm_zone_map_bio_end.isra.0 (STB_LOCAL)
ffffffff81ef60b0-ffffffff81ef60d2: dm_zone_map_bio_end.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09580)
Location: drivers/md/dm-zone.c:424
Inline: True
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81d09580-ffffffff81d09682: dm_zone_map_bio_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72850)
Location: drivers/md/dm-zone.c:423
Inline: True
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81d72850-ffffffff81d72954: dm_zone_map_bio_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device *md, unsigned int zno, struct orig_bio_details *orig_bio_details, unsigned int nr_sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:423
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81e29a00-ffffffff81e29afe: dm_zone_map_bio_end (STB_LOCAL)
ffffffff8220b144-ffffffff8220b164: dm_zone_map_bio_end.cold (STB_LOCAL)
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
</ul>

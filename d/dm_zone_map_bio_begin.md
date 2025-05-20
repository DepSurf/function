# Function: <code>dm_zone_map_bio_begin</code>

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
bool dm_zone_map_bio_begin(struct mapped_device *md, struct bio *orig_bio, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:369
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81a056e0-ffffffff81a05917: dm_zone_map_bio_begin (STB_LOCAL)
ffffffff81d29d99-ffffffff81d29dc9: dm_zone_map_bio_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool dm_zone_map_bio_begin(struct mapped_device *md, unsigned int zno, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:373
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81b6d410-ffffffff81b6d5f4: dm_zone_map_bio_begin (STB_LOCAL)
ffffffff81ef60d2-ffffffff81ef60e3: dm_zone_map_bio_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dm_zone_map_bio_begin(struct mapped_device *md, unsigned int zno, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09780)
Location: drivers/md/dm-zone.c:368
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81d09780-ffffffff81d09980: dm_zone_map_bio_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dm_zone_map_bio_begin(struct mapped_device *md, unsigned int zno, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72a50)
Location: drivers/md/dm-zone.c:367
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81d72a50-ffffffff81d72c4c: dm_zone_map_bio_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dm_zone_map_bio_begin(struct mapped_device *md, unsigned int zno, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:367
Inline: False
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81e29b10-ffffffff81e29d23: dm_zone_map_bio_begin (STB_LOCAL)
ffffffff8220b164-ffffffff8220b1a6: dm_zone_map_bio_begin.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int zno</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bio *orig_bio</code>
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

# Function: <code>dm_zone_revalidate_cb</code>

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
int dm_zone_revalidate_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:179
Inline: False
```
**Symbols:**

```
ffffffff81a05920-ffffffff81a05a57: dm_zone_revalidate_cb (STB_LOCAL)
ffffffff81d29dc9-ffffffff81d29de5: dm_zone_revalidate_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_zone_revalidate_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:178
Inline: False
```
**Symbols:**

```
ffffffff81b6d600-ffffffff81b6d743: dm_zone_revalidate_cb (STB_LOCAL)
ffffffff81ef60e3-ffffffff81ef60ff: dm_zone_revalidate_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_zone_revalidate_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09990)
Location: drivers/md/dm-zone.c:176
Inline: False
```
**Symbols:**

```
ffffffff81d09990-ffffffff81d09af1: dm_zone_revalidate_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_zone_revalidate_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d726f0)
Location: drivers/md/dm-zone.c:177
Inline: False
```
**Symbols:**

```
ffffffff81d726f0-ffffffff81d7283c: dm_zone_revalidate_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_zone_revalidate_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e29780)
Location: drivers/md/dm-zone.c:177
Inline: False
```
**Symbols:**

```
ffffffff81e29780-ffffffff81e298cc: dm_zone_revalidate_cb (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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

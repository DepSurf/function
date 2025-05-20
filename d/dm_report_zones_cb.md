# Function: <code>dm_report_zones_cb</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81976ca0)
Location: drivers/md/dm.c:448
Inline: False
```
**Symbols:**

```
ffffffff81976ca0-ffffffff81976d27: dm_report_zones_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b880)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff8197b880-ffffffff8197b907: dm_report_zones_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8195fa60)
Location: drivers/md/dm.c:448
Inline: False
```
**Symbols:**

```
ffffffff8195fa60-ffffffff8195fae3: dm_report_zones_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a05380)
Location: drivers/md/dm-zone.c:76
Inline: False
```
**Symbols:**

```
ffffffff81a05380-ffffffff81a05403: dm_report_zones_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6d0f0)
Location: drivers/md/dm-zone.c:76
Inline: False
```
**Symbols:**

```
ffffffff81b6d0f0-ffffffff81b6d197: dm_report_zones_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d093c0)
Location: drivers/md/dm-zone.c:76
Inline: False
```
**Symbols:**

```
ffffffff81d093c0-ffffffff81d09467: dm_report_zones_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72540)
Location: drivers/md/dm-zone.c:77
Inline: False
```
**Symbols:**

```
ffffffff81d72540-ffffffff81d725e7: dm_report_zones_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_report_zones_cb(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e29610)
Location: drivers/md/dm-zone.c:77
Inline: False
```
**Symbols:**

```
ffffffff81e29610-ffffffff81e296b7: dm_report_zones_cb (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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

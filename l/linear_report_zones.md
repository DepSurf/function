# Function: <code>linear_report_zones</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff8183a010)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff8183a010-ffffffff8183a085: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff8187cba0)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff8187cba0-ffffffff8187cc12: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff818ae980)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff818ae980-ffffffff818ae9f2: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff8197ec50)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff8197ec50-ffffffff8197ec87: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81983060)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff81983060-ffffffff81983097: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff819674a0)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff819674a0-ffffffff819674d7: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81a0f6a0)
Location: drivers/md/dm-linear.c:145
Inline: False
```
**Symbols:**

```
ffffffff81a0f6a0-ffffffff81a0f6cf: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81b77c40)
Location: drivers/md/dm-linear.c:136
Inline: False
```
**Symbols:**

```
ffffffff81b77c40-ffffffff81b77c7e: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81d15180)
Location: drivers/md/dm-linear.c:136
Inline: False
```
**Symbols:**

```
ffffffff81d15180-ffffffff81d151be: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81d7e2f0)
Location: drivers/md/dm-linear.c:137
Inline: False
```
**Symbols:**

```
ffffffff81d7e2f0-ffffffff81d7e32e: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81e35970)
Location: drivers/md/dm-linear.c:137
Inline: False
```
**Symbols:**

```
ffffffff81e35970-ffffffff81e359ae: linear_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffff800010b054f0)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffff800010b054f0-ffff800010b05594: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (c0be41ac)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
c0be41ac-c0be4240: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (c000000000bf5910)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
c000000000bf5910-c000000000bf59f0: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffe0006f44ac)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffe0006f44ac-ffffffe0006f4522: linear_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81854800)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff81854800-ffffffff81854872: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff8181be10)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff8181be10-ffffffff8181be82: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff818a3e30)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff818a3e30-ffffffff818a3ea2: linear_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int linear_report_zones(struct dm_target *ti, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff818c0070)
Location: drivers/md/dm-linear.c:139
Inline: False
```
**Symbols:**

```
ffffffff818c0070-ffffffff818c00e2: linear_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_report_zones_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t sector</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone *zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>ti, sector, zones, nr_zones</code> ➡️ <code>ti, args, nr_zones</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int *nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

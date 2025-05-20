# Function: <code>mmc_blk_alloc_req</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mmc_blk_data *mmc_blk_alloc_req(struct mmc_card *card, struct device *parent, sector_t size, bool default_ro, const char *subname, int area_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b3f7b8)
Location: drivers/mmc/core/block.c:2245
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffff800010b3f7b8-ffff800010b3fad8: mmc_blk_alloc_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mmc_blk_data *mmc_blk_alloc_req(struct mmc_card *card, struct device *parent, sector_t size, bool default_ro, const char *subname, int area_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c19f7c)
Location: drivers/mmc/core/block.c:2245
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
c0c19f7c-c0c1a288: mmc_blk_alloc_req (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mmc_blk_data *mmc_blk_alloc_req(struct mmc_card *card, struct device *parent, sector_t size, bool default_ro, const char *subname, int area_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe0007176a8)
Location: drivers/mmc/core/block.c:2245
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe0007176a8-ffffffe00071793c: mmc_blk_alloc_req (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>

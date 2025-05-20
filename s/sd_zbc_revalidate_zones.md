# Function: <code>sd_zbc_revalidate_zones</code>

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
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp, u32 zone_blocks, unsigned int nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848da0)
Location: drivers/scsi/sd_zbc.c:682
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81848da0-ffffffff81848fec: sd_zbc_revalidate_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818598b0)
Location: drivers/scsi/sd_zbc.c:683
Inline: False
```
**Symbols:**

```
ffffffff818598b0-ffffffff81859bf2: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183c5f0)
Location: drivers/scsi/sd_zbc.c:702
Inline: False
```
**Symbols:**

```
ffffffff8183c5f0-ffffffff8183c929: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:701
Inline: False
```
**Symbols:**

```
ffffffff81d0d244-ffffffff81d0d261: sd_zbc_revalidate_zones.cold (STB_LOCAL)
ffffffff818c8f50-ffffffff818c9295: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:820
Inline: False
```
**Symbols:**

```
ffffffff81ed617e-ffffffff81ed619b: sd_zbc_revalidate_zones.cold (STB_LOCAL)
ffffffff81a164d0-ffffffff81a16819: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:826
Inline: False
```
**Symbols:**

```
ffffffff8209c2eb-ffffffff8209c308: sd_zbc_revalidate_zones.cold (STB_LOCAL)
ffffffff81b972e0-ffffffff81b97625: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:828
Inline: False
```
**Symbols:**

```
ffffffff8211d22f-ffffffff8211d251: sd_zbc_revalidate_zones.cold (STB_LOCAL)
ffffffff81bed8a0-ffffffff81bedbdd: sd_zbc_revalidate_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:828
Inline: False
```
**Symbols:**

```
ffffffff821fb24a-ffffffff821fb289: sd_zbc_revalidate_zones.cold (STB_LOCAL)
ffffffff81c42f90-ffffffff81c43310: sd_zbc_revalidate_zones (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 zone_blocks</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_zones</code>
</li>
</ul>
</details>
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

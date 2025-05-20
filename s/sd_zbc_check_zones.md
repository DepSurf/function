# Function: <code>sd_zbc_check_zones</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8172585a)
Location: drivers/scsi/sd_zbc.c:319
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81760eba)
Location: drivers/scsi/sd_zbc.c:342
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81784e7a)
Location: drivers/scsi/sd_zbc.c:338
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
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
int sd_zbc_check_zones(struct scsi_disk *sdkp, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098b220)
Location: drivers/scsi/sd_zbc.c:338
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffff80001098b220-ffff80001098b600: sd_zbc_check_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_zbc_check_zones(struct scsi_disk *sdkp, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5d4d8)
Location: drivers/scsi/sd_zbc.c:338
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
c0a5d4d8-c0a5d8dc: sd_zbc_check_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_zbc_check_zones(struct scsi_disk *sdkp, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4bdc0)
Location: drivers/scsi/sd_zbc.c:338
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
c000000000a4bdc0-c000000000a4c248: sd_zbc_check_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_zbc_check_zones(struct scsi_disk *sdkp, u32 *zblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005ef5fe)
Location: drivers/scsi/sd_zbc.c:338
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffe0005ef5fe-ffffffe0005ef9f2: sd_zbc_check_zones (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8173956a)
Location: drivers/scsi/sd_zbc.c:338
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8171b20a)
Location: drivers/scsi/sd_zbc.c:338
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81779cfa)
Location: drivers/scsi/sd_zbc.c:338
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81793b2a)
Location: drivers/scsi/sd_zbc.c:338
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

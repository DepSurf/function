# Function: <code>scsi_get_vpd_size</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_get_vpd_size(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7e40)
Location: drivers/scsi/scsi.c:324
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff819f7e40-ffffffff819f7f03: scsi_get_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_get_vpd_size(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75750)
Location: drivers/scsi/scsi.c:324
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81b75750-ffffffff81b75813: scsi_get_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_get_vpd_size(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc9080)
Location: drivers/scsi/scsi.c:331
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81bc9080-ffffffff81bc9149: scsi_get_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_get_vpd_size(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:336
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81c1d430-ffffffff81c1d574: scsi_get_vpd_size (STB_LOCAL)
ffffffff821fa6e3-ffffffff821fa6fe: scsi_get_vpd_size.cold (STB_LOCAL)
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

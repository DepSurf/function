# Function: <code>sd_zbc_release_disk</code>

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
void sd_zbc_release_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81849660)
Location: drivers/scsi/sd_zbc.c:667
Inline: False
Direct callers:
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81849660-ffffffff818496a1: sd_zbc_release_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sd_zbc_release_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81859860)
Location: drivers/scsi/sd_zbc.c:668
Inline: False
Direct callers:
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81859860-ffffffff818598a1: sd_zbc_release_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sd_zbc_release_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183c560)
Location: drivers/scsi/sd_zbc.c:689
Inline: False
Direct callers:
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff8183c560-ffffffff8183c5ef: sd_zbc_release_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sd_zbc_release_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818c8ec0)
Location: drivers/scsi/sd_zbc.c:688
Inline: False
Direct callers:
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff818c8ec0-ffffffff818c8f4f: sd_zbc_release_disk (STB_GLOBAL)
```
</details>
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
</ul>

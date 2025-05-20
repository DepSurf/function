# Function: <code>scsi_disk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bb7d0)
Location: drivers/scsi/sd.c:586
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff815bb7d0-ffffffff815bb811: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81613ec0)
Location: drivers/scsi/sd.c:586
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81613ec0-ffffffff81613f01: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81643830)
Location: drivers/scsi/sd.c:593
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81643830-ffffffff81643871: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81657f40)
Location: drivers/scsi/sd.c:623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81657f40-ffffffff81657f81: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c1400)
Location: drivers/scsi/sd.c:631
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff816c1400-ffffffff816c1441: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fda50)
Location: drivers/scsi/sd.c:631
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff816fda50-ffffffff816fda91: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81720620)
Location: drivers/scsi/sd.c:638
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81720620-ffffffff81720661: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175bcb0)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff8175bcb0-ffffffff8175bcf1: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177fbc0)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff8177fbc0-ffffffff8177fc01: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81844ae9)
Location: drivers/scsi/sd.c:654
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81854e04)
Location: drivers/scsi/sd.c:686
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818387f4)
Location: drivers/scsi/sd.c:686
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c3db4)
Location: drivers/scsi/sd.c:685
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010986238)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffff800010986238-ffff800010986294: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a59404)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
c0a59404-c0a5944c: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a469d0)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
c000000000a469d0-c000000000a46a54: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005eb634)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffe0005eb634-ffffffe0005eb692: scsi_disk_put (STB_LOCAL)
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
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817342b0)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff817342b0-ffffffff817342f1: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81715f50)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81715f50-ffffffff81715f91: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81774a40)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff81774a40-ffffffff81774a81: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_disk_put(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178e820)
Location: drivers/scsi/sd.c:640
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
**Symbols:**

```
ffffffff8178e820-ffffffff8178e861: scsi_disk_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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

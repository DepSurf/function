# Function: <code>sd_zbc_check_zoned_characteristics</code>

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
In drivers/scsi/sd_zbc.c (ffffffff81725804)
Location: drivers/scsi/sd_zbc.c:265
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
In drivers/scsi/sd_zbc.c (ffffffff81760e64)
Location: drivers/scsi/sd_zbc.c:290
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
In drivers/scsi/sd_zbc.c (ffffffff81784e24)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818488a0)
Location: drivers/scsi/sd_zbc.c:544
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff818488a0-ffffffff81848a04: sd_zbc_check_zoned_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81858e50)
Location: drivers/scsi/sd_zbc.c:545
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81858e50-ffffffff81858fb4: sd_zbc_check_zoned_characteristics (STB_LOCAL)
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
In drivers/scsi/sd_zbc.c (ffffffff8183ca0a)
Location: drivers/scsi/sd_zbc.c:548
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
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
In drivers/scsi/sd_zbc.c (ffffffff818c937a)
Location: drivers/scsi/sd_zbc.c:547
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:630
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81a153e0-ffffffff81a1563e: sd_zbc_check_zoned_characteristics (STB_LOCAL)
ffffffff81ed5e75-ffffffff81ed5ea0: sd_zbc_check_zoned_characteristics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:636
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81b96310-ffffffff81b9656e: sd_zbc_check_zoned_characteristics (STB_LOCAL)
ffffffff8209c051-ffffffff8209c07c: sd_zbc_check_zoned_characteristics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:638
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81bec620-ffffffff81bec855: sd_zbc_check_zoned_characteristics (STB_LOCAL)
ffffffff8211cf45-ffffffff8211cf6a: sd_zbc_check_zoned_characteristics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk *sdkp, unsigned char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:638
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81c41ce0-ffffffff81c41f15: sd_zbc_check_zoned_characteristics (STB_LOCAL)
ffffffff821fae5d-ffffffff821fae82: sd_zbc_check_zoned_characteristics.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098ba50)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5de0c)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4c780)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005f00c2)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81739514)
Location: drivers/scsi/sd_zbc.c:286
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
In drivers/scsi/sd_zbc.c (ffffffff8171b1b4)
Location: drivers/scsi/sd_zbc.c:286
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
In drivers/scsi/sd_zbc.c (ffffffff81779ca4)
Location: drivers/scsi/sd_zbc.c:286
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
In drivers/scsi/sd_zbc.c (ffffffff81793ad4)
Location: drivers/scsi/sd_zbc.c:286
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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

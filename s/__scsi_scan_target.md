# Function: <code>__scsi_scan_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, int rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b3730)
Location: drivers/scsi/scsi_scan.c:1533
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff815b3730-ffffffff815b3984: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160bb90)
Location: drivers/scsi/scsi_scan.c:1555
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8160bb90-ffffffff8160bddd: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163b430)
Location: drivers/scsi/scsi_scan.c:1549
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8163b430-ffffffff8163b67d: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164f800)
Location: drivers/scsi/scsi_scan.c:1532
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8164f800-ffffffff8164fdfb: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b8e00)
Location: drivers/scsi/scsi_scan.c:1538
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff816b8e00-ffffffff816b9405: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1538
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff816f5140-ffffffff816f5756: __scsi_scan_target (STB_LOCAL)
ffffffff816f5f4d-ffffffff816f5f96: __scsi_scan_target.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1530
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81717aa0-ffffffff81718078: __scsi_scan_target (STB_LOCAL)
ffffffff8171885d-ffffffff817188a6: __scsi_scan_target.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff817535d0-ffffffff817537db: __scsi_scan_target (STB_LOCAL)
ffffffff81753f8c-ffffffff81753fa7: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81777850-ffffffff81777a5b: __scsi_scan_target (STB_LOCAL)
ffffffff8177820c-ffffffff81778227: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1530
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8183a7b0-ffffffff8183a9bb: __scsi_scan_target (STB_LOCAL)
ffffffff8183b164-ffffffff8183b17f: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1530
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8184b170-ffffffff8184b38a: __scsi_scan_target (STB_LOCAL)
ffffffff81c16a10-ffffffff81c16a2b: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1548
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8182e4e0-ffffffff8182e6f5: __scsi_scan_target (STB_LOCAL)
ffffffff81c086ad-ffffffff81c086c8: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1557
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff818ba2b0-ffffffff818ba4c5: __scsi_scan_target (STB_LOCAL)
ffffffff81d0c792-ffffffff81d0c7ad: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1633
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81a05d10-ffffffff81a05f35: __scsi_scan_target (STB_LOCAL)
ffffffff81ed5691-ffffffff81ed56ac: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b84aa0)
Location: drivers/scsi/scsi_scan.c:1633
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81b84aa0-ffffffff81b84cd0: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd8810)
Location: drivers/scsi/scsi_scan.c:1645
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81bd8810-ffffffff81bd8a50: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2d510)
Location: drivers/scsi/scsi_scan.c:1662
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81c2d510-ffffffff81c2d750: __scsi_scan_target (STB_LOCAL)
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
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097bdd0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffff80001097bdd0-ffff80001097c01c: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4f728)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
c0a4f728-c0a4fa08: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a37140)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
c000000000a37140-c000000000a37424: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e2f0e)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffe0005e2f0e-ffffffe0005e30ec: __scsi_scan_target (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8172bf40-ffffffff8172c14b: __scsi_scan_target (STB_LOCAL)
ffffffff8172c8fc-ffffffff8172c917: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81705360-ffffffff8170556b: __scsi_scan_target (STB_LOCAL)
ffffffff81705d1c-ffffffff81705d37: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff8176ad10-ffffffff8176af1b: __scsi_scan_target (STB_LOCAL)
ffffffff8176b6cc-ffffffff8176b6e7: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __scsi_scan_target(struct device *parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1531
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
**Symbols:**

```
ffffffff81786460-ffffffff8178666b: __scsi_scan_target (STB_LOCAL)
ffffffff81786e0c-ffffffff81786e27: __scsi_scan_target.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rescan</code> ➡️ <code>enum scsi_scan_mode rescan</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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

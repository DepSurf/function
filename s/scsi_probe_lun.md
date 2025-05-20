# Function: <code>scsi_probe_lun</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b2006)
Location: drivers/scsi/scsi_scan.c:559
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160a446)
Location: drivers/scsi/scsi_scan.c:567
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81639d26)
Location: drivers/scsi/scsi_scan.c:565
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164e8a6)
Location: drivers/scsi/scsi_scan.c:567
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b7b46)
Location: drivers/scsi/scsi_scan.c:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f40ef)
Location: drivers/scsi/scsi_scan.c:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81716738)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff817527ee)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff81776a6e)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:559
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818392e0-ffffffff81839712: scsi_probe_lun.constprop.0 (STB_LOCAL)
ffffffff8183b0d1-ffffffff8183b102: scsi_probe_lun.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:559
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81849b60-ffffffff81849f92: scsi_probe_lun.constprop.0 (STB_LOCAL)
ffffffff81c16954-ffffffff81c16985: scsi_probe_lun.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:578
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8182cf90-ffffffff8182d3c2: scsi_probe_lun.constprop.0 (STB_LOCAL)
ffffffff81c0862f-ffffffff81c08660: scsi_probe_lun.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:584
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818b8d30-ffffffff818b9166: scsi_probe_lun.constprop.0 (STB_LOCAL)
ffffffff81d0c6e5-ffffffff81d0c716: scsi_probe_lun.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:643
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81a04610-ffffffff81a04af4: scsi_probe_lun.constprop.0 (STB_LOCAL)
ffffffff81ed561e-ffffffff81ed5648: scsi_probe_lun.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83230)
Location: drivers/scsi/scsi_scan.c:643
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81b83230-ffffffff81b8375f: scsi_probe_lun.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd6f60)
Location: drivers/scsi/scsi_scan.c:643
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81bd6f60-ffffffff81bd74b6: scsi_probe_lun.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2bc00)
Location: drivers/scsi/scsi_scan.c:643
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81c2bc00-ffffffff81c2c159: scsi_probe_lun.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (ffff80001097ad50)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4e41c)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c0a4e41c-c0a4e900: scsi_probe_lun.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (c000000000a35d20)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffe0005e1f04)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff8172b15e)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff8170457e)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff81769f2e)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
In drivers/scsi/scsi_scan.c (ffffffff8178567e)
Location: drivers/scsi/scsi_scan.c:560
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
</ul>

## Differences

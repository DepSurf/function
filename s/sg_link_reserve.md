# Function: <code>sg_link_reserve</code>

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
In drivers/scsi/sg.c (ffffffff815c5898)
Location: drivers/scsi/sg.c:1982
Inline: True
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
In drivers/scsi/sg.c (ffffffff8161dfbc)
Location: drivers/scsi/sg.c:1983
Inline: True
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
In drivers/scsi/sg.c (ffffffff8164eb68)
Location: drivers/scsi/sg.c:1980
Inline: True
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
In drivers/scsi/sg.c (ffffffff816635dc)
Location: drivers/scsi/sg.c:2009
Inline: True
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
In drivers/scsi/sg.c (ffffffff816ccc34)
Location: drivers/scsi/sg.c:2008
Inline: True
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
In drivers/scsi/sg.c (ffffffff81709570)
Location: drivers/scsi/sg.c:2041
Inline: True
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
In drivers/scsi/sg.c (ffffffff8172ba60)
Location: drivers/scsi/sg.c:2029
Inline: True
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
In drivers/scsi/sg.c (ffffffff817671a6)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff8178b196)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff8184d300)
Location: drivers/scsi/sg.c:2054
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8184d300-ffffffff8184d40b: sg_link_reserve.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sg.c (ffffffff8185d7b0)
Location: drivers/scsi/sg.c:2047
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8185d7b0-ffffffff8185d8bb: sg_link_reserve.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sg.c (ffffffff81841fd6)
Location: drivers/scsi/sg.c:2041
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In drivers/scsi/sg.c (ffffffff818cec58)
Location: drivers/scsi/sg.c:2010
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a1b210)
Location: drivers/scsi/sg.c:2028
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9c379)
Location: drivers/scsi/sg.c:2011
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf2969)
Location: drivers/scsi/sg.c:2022
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c48259)
Location: drivers/scsi/sg.c:2021
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In drivers/scsi/sg.c (ffff80001099067c)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (c0a6407c)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (c000000000a54f2c)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffe0005f58ca)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff8173f886)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff81721526)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff81780016)
Location: drivers/scsi/sg.c:2024
Inline: True
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
In drivers/scsi/sg.c (ffffffff81799e06)
Location: drivers/scsi/sg.c:2024
Inline: True
```
</details>
</li>
</ul>

## Differences

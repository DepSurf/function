# Function: <code>copy_data_pages</code>

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
In kernel/power/snapshot.c (ffffffff810d1c1f)
Location: kernel/power/snapshot.c:1269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810d69c1)
Location: kernel/power/snapshot.c:1369
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810dd530)
Location: kernel/power/snapshot.c:1391
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810dc619)
Location: kernel/power/snapshot.c:1393
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810e4839)
Location: kernel/power/snapshot.c:1395
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810ed7bf)
Location: kernel/power/snapshot.c:1395
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810f8e27)
Location: kernel/power/snapshot.c:1396
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff8110149b)
Location: kernel/power/snapshot.c:1403
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff8110d8ce)
Location: kernel/power/snapshot.c:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff811185e0)
Location: kernel/power/snapshot.c:1409
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff811185e0-ffffffff811186f8: copy_data_pages.constprop.0 (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81bdfa7a)
Location: kernel/power/snapshot.c:1451
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81bdfa7a-ffffffff81bdfb95: copy_data_pages.constprop.0 (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81bd18a3)
Location: kernel/power/snapshot.c:1451
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81bd18a3-ffffffff81bd1aa0: copy_data_pages.constprop.0 (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81caa4ff)
Location: kernel/power/snapshot.c:1444
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81caa4ff-ffffffff81caa72c: copy_data_pages.constprop.0 (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81e5a92b)
Location: kernel/power/snapshot.c:1448
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81e5a92b-ffffffff81e5ab5d: copy_data_pages.constprop.0 (STB_LOCAL)
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
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1448
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81185e40-ffffffff811860a3: copy_data_pages.constprop.0 (STB_LOCAL)
ffffffff82058642-ffffffff8205866b: copy_data_pages.constprop.0.cold (STB_LOCAL)
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
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1500
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81197010-ffffffff81197285: copy_data_pages.constprop.0 (STB_LOCAL)
ffffffff820d6dd5-ffffffff820d6dfe: copy_data_pages.constprop.0.cold (STB_LOCAL)
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
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1527
Inline: True
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff811a5af0-ffffffff811a5dd7: copy_data_pages.constprop.0 (STB_LOCAL)
ffffffff821b206b-ffffffff821b2095: copy_data_pages.constprop.0.cold (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03c075c)
Location: kernel/power/snapshot.c:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81105aee)
Location: kernel/power/snapshot.c:1409
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810f6d8e)
Location: kernel/power/snapshot.c:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff81103d9e)
Location: kernel/power/snapshot.c:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff8110f18e)
Location: kernel/power/snapshot.c:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
</ul>

## Differences

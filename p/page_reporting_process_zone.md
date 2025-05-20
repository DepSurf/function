# Function: <code>page_reporting_process_zone</code>

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
int page_reporting_process_zone(struct page_reporting_dev_info *prdev, struct scatterlist *sgl, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff8130d350)
Location: mm/page_reporting.c:223
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8130d350-ffffffff8130d48f: page_reporting_process_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_reporting_process_zone(struct page_reporting_dev_info *prdev, struct scatterlist *sgl, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff813192a0)
Location: mm/page_reporting.c:223
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813192a0-ffffffff813193df: page_reporting_process_zone (STB_LOCAL)
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
In mm/page_reporting.c (ffffffff8131f503)
Location: mm/page_reporting.c:223
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
In mm/page_reporting.c (ffffffff8136c937)
Location: mm/page_reporting.c:228
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
In mm/page_reporting.c (ffffffff813eab74)
Location: mm/page_reporting.c:228
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
In mm/page_reporting.c (ffffffff81472d24)
Location: mm/page_reporting.c:260
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
In mm/page_reporting.c (ffffffff814a7494)
Location: mm/page_reporting.c:260
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
In mm/page_reporting.c (ffffffff814d84c3)
Location: mm/page_reporting.c:260
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>

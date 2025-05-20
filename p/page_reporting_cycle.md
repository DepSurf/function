# Function: <code>page_reporting_cycle</code>

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
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff8130d040)
Location: mm/page_reporting.c:109
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process_zone
  - mm/page_reporting.c:page_reporting_process_zone
```
**Symbols:**

```
ffffffff8130d040-ffffffff8130d349: page_reporting_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff81318f90)
Location: mm/page_reporting.c:109
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process_zone
  - mm/page_reporting.c:page_reporting_process_zone
```
**Symbols:**

```
ffffffff81318f90-ffffffff81319299: page_reporting_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff8131f180)
Location: mm/page_reporting.c:109
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8131f180-ffffffff8131f486: page_reporting_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:114
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8136c560-ffffffff8136c8bb: page_reporting_cycle (STB_LOCAL)
ffffffff81cc374a-ffffffff81cc376c: page_reporting_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:114
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813ea760-ffffffff813eaaf5: page_reporting_cycle (STB_LOCAL)
ffffffff81e75e55-ffffffff81e75e86: page_reporting_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:146
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff81472900-ffffffff81472c95: page_reporting_cycle (STB_LOCAL)
ffffffff820686b1-ffffffff820686e2: page_reporting_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:146
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff814a7070-ffffffff814a7404: page_reporting_cycle (STB_LOCAL)
ffffffff820e7fb4-ffffffff820e7fe5: page_reporting_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info *prdev, struct zone *zone, unsigned int order, unsigned int mt, struct scatterlist *sgl, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:146
Inline: False
Direct callers:
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff814d8070-ffffffff814d8404: page_reporting_cycle (STB_LOCAL)
ffffffff821c4cde-ffffffff821c4d0f: page_reporting_cycle.cold (STB_LOCAL)
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

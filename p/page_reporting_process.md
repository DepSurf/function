# Function: <code>page_reporting_process</code>

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
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff8130d490)
Location: mm/page_reporting.c:270
Inline: False
```
**Symbols:**

```
ffffffff8130d490-ffffffff8130d54f: page_reporting_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff813193e0)
Location: mm/page_reporting.c:270
Inline: False
```
**Symbols:**

```
ffffffff813193e0-ffffffff8131949f: page_reporting_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_reporting.c (ffffffff8131f490)
Location: mm/page_reporting.c:270
Inline: False
```
**Symbols:**

```
ffffffff8131f490-ffffffff8131f661: page_reporting_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:275
Inline: False
```
**Symbols:**

```
ffffffff8136c8c0-ffffffff8136ca9c: page_reporting_process (STB_LOCAL)
ffffffff81cc376c-ffffffff81cc378a: page_reporting_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:275
Inline: False
```
**Symbols:**

```
ffffffff813eab00-ffffffff813eaceb: page_reporting_process (STB_LOCAL)
ffffffff81e75e86-ffffffff81e75ea4: page_reporting_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:307
Inline: False
```
**Symbols:**

```
ffffffff81472cb0-ffffffff81472e9b: page_reporting_process (STB_LOCAL)
ffffffff820686e2-ffffffff82068700: page_reporting_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:307
Inline: False
```
**Symbols:**

```
ffffffff814a7420-ffffffff814a760b: page_reporting_process (STB_LOCAL)
ffffffff820e7fe5-ffffffff820e8003: page_reporting_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void page_reporting_process(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_reporting.c (0)
Location: mm/page_reporting.c:307
Inline: False
```
**Symbols:**

```
ffffffff814d8420-ffffffff814d863a: page_reporting_process (STB_LOCAL)
ffffffff821c4d0f-ffffffff821c4d2d: page_reporting_process.cold (STB_LOCAL)
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

# Function: <code>putback_inactive_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a3640)
Location: mm/vmscan.c:1486
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811a3640-ffffffff811a395f: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b9ff0)
Location: mm/vmscan.c:1588
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811b9ff0-ffffffff811ba443: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ca680)
Location: mm/vmscan.c:1622
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811ca680-ffffffff811caad1: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d31e0)
Location: mm/vmscan.c:1661
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811d31e0-ffffffff811d3636: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e8730)
Location: mm/vmscan.c:1678
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811e8730-ffffffff811e8b8c: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81209c00)
Location: mm/vmscan.c:1656
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81209c00-ffffffff8120a0ad: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void putback_inactive_pages(struct lruvec *lruvec, struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121c8e0)
Location: mm/vmscan.c:1823
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8121c8e0-ffffffff8121cd92: putback_inactive_pages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
</ul>

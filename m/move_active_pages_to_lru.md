# Function: <code>move_active_pages_to_lru</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2190)
Location: mm/vmscan.c:1720
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811a2190-ffffffff811a2395: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b7c30)
Location: mm/vmscan.c:1843
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811b7c30-ffffffff811b7edf: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8280)
Location: mm/vmscan.c:1877
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811c8280-ffffffff811c853f: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d0c10)
Location: mm/vmscan.c:1904
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811d0c10-ffffffff811d0f2a: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e6100)
Location: mm/vmscan.c:1928
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811e6100-ffffffff811e6420: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81207670)
Location: mm/vmscan.c:1858
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff81207670-ffffffff812079cb: move_active_pages_to_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int move_active_pages_to_lru(struct lruvec *lruvec, struct list_head *list, struct list_head *pages_to_free, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121a1f0)
Location: mm/vmscan.c:2025
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff8121a1f0-ffffffff8121a54f: move_active_pages_to_lru (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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

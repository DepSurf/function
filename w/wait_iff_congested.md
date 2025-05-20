# Function: <code>wait_iff_congested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int wait_iff_congested(struct zone *zone, int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae850)
Location: mm/backing-dev.c:968
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811ae850-ffffffff811ae9c6: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int wait_iff_congested(struct pglist_data *pgdat, int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7c20)
Location: mm/backing-dev.c:986
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811c7c20-ffffffff811c7d74: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int wait_iff_congested(struct pglist_data *pgdat, int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7d40)
Location: mm/backing-dev.c:992
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811d7d40-ffffffff811d7e94: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int wait_iff_congested(struct pglist_data *pgdat, int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0920)
Location: mm/backing-dev.c:1037
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811e0920-ffffffff811e0a74: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int wait_iff_congested(struct pglist_data *pgdat, int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6910)
Location: mm/backing-dev.c:1052
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811f6910-ffffffff811f6a67: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217bf0)
Location: mm/backing-dev.c:1045
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81217bf0-ffffffff81217d38: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122ab00)
Location: mm/backing-dev.c:1048
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8122ab00-ffffffff8122ac48: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123a770)
Location: mm/backing-dev.c:1035
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8123a770-ffffffff8123a8b4: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248a80)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81248a80-ffffffff81248bc4: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81276cc0)
Location: mm/backing-dev.c:1114
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81276cc0-ffffffff81276e04: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281590)
Location: mm/backing-dev.c:983
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81281590-ffffffff812816c3: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286440)
Location: mm/backing-dev.c:982
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81286440-ffffffff81286573: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5790)
Location: mm/backing-dev.c:1065
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812c5790-ffffffff812c58fd: wait_iff_congested (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102dd878)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffff8000102dd878-ffff8000102dd9f8: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c05032cc)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c05032cc-c0503468: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039d4a0)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c00000000039d4a0-c00000000039d67c: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f5fc4)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffe0001f5fc4-ffffffe0001f610a: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812410d0)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812410d0-ffffffff81241214: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812340d0)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812340d0-ffffffff81234214: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123ee70)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8123ee70-ffffffff8123efb4: wait_iff_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int wait_iff_congested(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124e5b0)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8124e5b0-ffffffff8124e708: wait_iff_congested (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param reordered. </b>
<code>pgdat, sync, timeout</code> ➡️ <code>sync, timeout</code>
</li>
</ul>
</details>
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

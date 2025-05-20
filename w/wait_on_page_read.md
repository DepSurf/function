# Function: <code>wait_on_page_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *wait_on_page_read(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cbc0)
Location: mm/filemap.c:2193
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
```
**Symbols:**

```
ffffffff8118cbc0-ffffffff8118cc0f: wait_on_page_read (STB_LOCAL)
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
In mm/filemap.c (ffffffff811a150b)
Location: mm/filemap.c:2349
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff811b1268)
Location: mm/filemap.c:2465
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff811b8668)
Location: mm/filemap.c:2599
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff811ccdfa)
Location: mm/filemap.c:2769
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff811edf0c)
Location: mm/filemap.c:2769
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff811ff57c)
Location: mm/filemap.c:2746
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff81216540)
Location: mm/filemap.c:2790
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff81223e50)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252d40)
Location: mm/filemap.c:2745
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d90d)
Location: mm/filemap.c:3062
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff8126067c)
Location: mm/filemap.c:3309
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff8129d06d)
Location: mm/filemap.c:3422
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1738)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (c04de2a8)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (c0000000003671f4)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffe0001d6e42)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff8121c4a0)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff8120f68a)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff8121a240)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
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
In mm/filemap.c (ffffffff81229317)
Location: mm/filemap.c:2744
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

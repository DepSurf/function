# Function: <code>page_cache_delete_batch</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200865)
Location: mm/filemap.c:290
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff81218495)
Location: mm/filemap.c:292
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff81225d25)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_cache_delete_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124f190)
Location: mm/filemap.c:294
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff8124f190-ffffffff8124f3fb: page_cache_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_cache_delete_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259460)
Location: mm/filemap.c:295
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff81259460-ffffffff812596b8: page_cache_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_cache_delete_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d7b0)
Location: mm/filemap.c:286
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff8125d7b0-ffffffff8125da08: page_cache_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_cache_delete_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299a60)
Location: mm/filemap.c:287
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff81299a60-ffffffff81299c9f: page_cache_delete_batch (STB_LOCAL)
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
In mm/filemap.c (ffffffff812f52ac)
Location: mm/filemap.c:277
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff8135f11c)
Location: mm/filemap.c:277
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff81390236)
Location: mm/filemap.c:282
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff813b9c76)
Location: mm/filemap.c:277
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffff8000102b2ea0)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (c04e00a0)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (c00000000036994c)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffe0001d86cc)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff8121e375)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff81211535)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff8121c115)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
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
In mm/filemap.c (ffffffff8122b185)
Location: mm/filemap.c:294
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
</details>
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
</ul>

# Function: <code>iomap_do_writepage</code>

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
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac9d0)
Location: fs/iomap/buffered-io.c:1477
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage
```
**Symbols:**

```
ffffffff813ac9d0-ffffffff813acbb0: iomap_do_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bd490)
Location: fs/iomap/buffered-io.c:1437
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage
```
**Symbols:**

```
ffffffff813bd490-ffffffff813bd5aa: iomap_do_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c39e0)
Location: fs/iomap/buffered-io.c:1433
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage
```
**Symbols:**

```
ffffffff813c39e0-ffffffff813c3ae6: iomap_do_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81413f20)
Location: fs/iomap/buffered-io.c:1394
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage
```
**Symbols:**

```
ffffffff81413f20-ffffffff81414023: iomap_do_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1427
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage
```
**Symbols:**

```
ffffffff8148a480-ffffffff8148a7b9: iomap_do_writepage (STB_LOCAL)
ffffffff81e7a1b3-ffffffff81e7a23d: iomap_do_writepage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_do_writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1689
Inline: False
```
**Symbols:**

```
ffffffff8151de60-ffffffff8151e091: iomap_do_writepage (STB_LOCAL)
ffffffff8206b11e-ffffffff8206b1a8: iomap_do_writepage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_do_writepage(struct folio *folio, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1708
Inline: False
```
**Symbols:**

```
ffffffff81556010-ffffffff815561f2: iomap_do_writepage (STB_LOCAL)
ffffffff820eb078-ffffffff820eb0f6: iomap_do_writepage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_do_writepage(struct folio *folio, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff8158c4d0-ffffffff8158c6d0: iomap_do_writepage (STB_LOCAL)
ffffffff821c8173-ffffffff821c81f5: iomap_do_writepage.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

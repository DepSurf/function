# Function: <code>balance_dirty_pages_ratelimited_flags</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int balance_dirty_pages_ratelimited_flags(struct address_space *mapping, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81369280)
Location: mm/page-writeback.c:1992
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff81369280-ffffffff8136962c: balance_dirty_pages_ratelimited_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int balance_dirty_pages_ratelimited_flags(struct address_space *mapping, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139b420)
Location: mm/page-writeback.c:1992
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8139b420-ffffffff8139b7cc: balance_dirty_pages_ratelimited_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int balance_dirty_pages_ratelimited_flags(struct address_space *mapping, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c5390)
Location: mm/page-writeback.c:1992
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff813c5390-ffffffff813c573c: balance_dirty_pages_ratelimited_flags (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

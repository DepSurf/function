# Function: <code>__invalidate_mapping_pages</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c230)
Location: mm/truncate.c:531
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff8126c230-ffffffff8126c5f5: __invalidate_mapping_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81271130)
Location: mm/truncate.c:467
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff81271130-ffffffff81271351: __invalidate_mapping_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ae670)
Location: mm/truncate.c:468
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff812ae670-ffffffff812ae8d7: __invalidate_mapping_pages (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>

# Function: <code>check_and_migrate_movable_pages</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296e60)
Location: mm/gup.c:1635
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffff81296e60-ffffffff81297139: check_and_migrate_movable_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7810)
Location: mm/gup.c:1723
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffff812d7810-ffffffff812d7aec: check_and_migrate_movable_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337a80)
Location: mm/gup.c:1904
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffff81337a80-ffffffff81337dd4: check_and_migrate_movable_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813af1a0)
Location: mm/gup.c:2016
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffff813af1a0-ffffffff813af40a: check_and_migrate_movable_pages (STB_LOCAL)
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
In mm/gup.c (ffffffff813e6703)
Location: mm/gup.c:2148
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140dff0)
Location: mm/gup.c:2174
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffff8140dff0-ffffffff8140e251: check_and_migrate_movable_pages (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int gup_flags</code>
</li>
</ul>
</details>
</li>
</ul>

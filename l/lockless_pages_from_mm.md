# Function: <code>lockless_pages_from_mm</code>

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
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295030)
Location: mm/gup.c:2517
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81295030-ffffffff8129513d: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a9f0)
Location: mm/gup.c:2583
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff8129a9f0-ffffffff8129ab07: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db3a0)
Location: mm/gup.c:2678
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff812db3a0-ffffffff812db4b7: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133af80)
Location: mm/gup.c:2826
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff8133af80-ffffffff8133b161: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2bc0)
Location: mm/gup.c:2851
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff813b2bc0-ffffffff813b2dbc: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7830)
Location: mm/gup.c:3110
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff813e7830-ffffffff813e7a2d: lockless_pages_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int lockless_pages_from_mm(long unsigned int start, long unsigned int end, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814124a0)
Location: mm/gup.c:3128
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff814124a0-ffffffff81412694: lockless_pages_from_mm (STB_LOCAL)
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

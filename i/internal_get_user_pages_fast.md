# Function: <code>internal_get_user_pages_fast</code>

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
int internal_get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b370)
Location: mm/gup.c:2739
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff8128b370-ffffffff8128b540: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295140)
Location: mm/gup.c:2564
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff81295140-ffffffff8129538b: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129ab10)
Location: mm/gup.c:2630
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff8129ab10-ffffffff8129ad09: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db4c0)
Location: mm/gup.c:2725
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff812db4c0-ffffffff812db6d1: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b170)
Location: mm/gup.c:2875
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff8133b170-ffffffff8133b3cf: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2dd0)
Location: mm/gup.c:2900
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast_only
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff813b2dd0-ffffffff813b2f0c: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7a40)
Location: mm/gup.c:3159
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff813e7a40-ffffffff813e7bd9: internal_get_user_pages_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814126b0)
Location: mm/gup.c:3177
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast_only
```
**Symbols:**

```
ffffffff814126b0-ffffffff81412849: internal_get_user_pages_fast (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>long unsigned int nr_pages</code>
</li>
</ul>
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

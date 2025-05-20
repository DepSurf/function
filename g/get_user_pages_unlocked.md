# Function: <code>get_user_pages_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int get_user_pages_unlocked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bb2c0)
Location: mm/gup.c:791
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:get_user_pages_fast
  - mm/util.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff811bb2c0-ffffffff811bb495: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5bc0)
Location: mm/gup.c:898
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:get_user_pages_fast
  - mm/util.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff811d5bc0-ffffffff811d5d9e: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e5ba0)
Location: mm/gup.c:900
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:get_user_pages_fast
  - mm/util.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff811e5ba0-ffffffff811e5d55: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0220)
Location: mm/gup.c:981
Inline: False
Direct callers:
  - mm/util.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff811f0220-ffffffff811f03c6: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81207660)
Location: mm/gup.c:1006
Inline: False
Direct callers:
  - mm/util.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81207660-ffffffff81207806: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81228760)
Location: mm/gup.c:1004
Inline: False
Direct callers:
  - mm/util.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81228760-ffffffff8122890f: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123bf80)
Location: mm/gup.c:1029
Inline: False
Direct callers:
  - mm/util.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff8123bf80-ffffffff8123c12f: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124d3c0)
Location: mm/gup.c:1678
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff8124d3c0-ffffffff8124d5a9: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125b8f0)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff8125b8f0-ffffffff8125bad9: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81289fe0)
Location: mm/gup.c:2065
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81289fe0-ffffffff8128a25f: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81293d00)
Location: mm/gup.c:1921
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81293d00-ffffffff81294010: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299690)
Location: mm/gup.c:1987
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81299690-ffffffff8129999b: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d9ff0)
Location: mm/gup.c:2075
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff812d9ff0-ffffffff812da319: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339a00)
Location: mm/gup.c:2205
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81339a00-ffffffff81339cff: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1bd0)
Location: mm/gup.c:2242
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff813b1bd0-ffffffff813b1cc6: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e5df0)
Location: mm/gup.c:2389
Inline: False
```
**Symbols:**

```
ffffffff813e5df0-ffffffff813e6121: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81410920)
Location: mm/gup.c:2407
Inline: False
```
**Symbols:**

```
ffffffff81410920-ffffffff81410c88: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2cf0)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffff8000102f2cf0-ffff8000102f2ee8: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05150d8)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
c05150d8-c0515314: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9550)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
c0000000003b9550-c0000000003b983c: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000205164)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffe000205164-ffffffe0002052ca: get_user_pages_unlocked (STB_GLOBAL)
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253f40)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81253f40-ffffffff81254129: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246b90)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81246b90-ffffffff81246d79: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251ce0)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81251ce0-ffffffff81251ec9: get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261690)
Location: mm/gup.c:1681
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81261690-ffffffff81261879: get_user_pages_unlocked (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages</code> ➡️ <code>start, nr_pages, write, force, pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, nr_pages, write, force, pages</code> ➡️ <code>start, nr_pages, pages, gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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

# Function: <code>bad_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81191d40)
Location: mm/page_alloc.c:400
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81191d40-ffffffff81191e36: bad_page.part.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a6390)
Location: mm/page_alloc.c:508
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff811a6390-ffffffff811a64b4: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6710)
Location: mm/page_alloc.c:513
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff811b6710-ffffffff811b682b: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be5d0)
Location: mm/page_alloc.c:529
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff811be5d0-ffffffff811be6ee: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3340)
Location: mm/page_alloc.c:544
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff811d3340-ffffffff811d345e: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff811f4690-ffffffff811f4700: bad_page (STB_LOCAL)
ffffffff811fac32-ffffffff811face5: bad_page.cold.113 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:550
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff81206ac0-ffffffff81206b30: bad_page (STB_LOCAL)
ffffffff8120d476-ffffffff8120d529: bad_page.cold.117 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:612
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff8126cb00-ffffffff8126cb70: bad_page (STB_LOCAL)
ffffffff8127396f-ffffffff81273a20: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff8127b910-ffffffff8127b980: bad_page (STB_LOCAL)
ffffffff812827df-ffffffff81282890: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:598
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_free_page_bad
```
**Symbols:**

```
ffffffff812adb80-ffffffff812adbe4: bad_page (STB_LOCAL)
ffffffff812b4891-ffffffff812b4925: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:598
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_free_page_bad
```
**Symbols:**

```
ffffffff812b9540-ffffffff812b95a4: bad_page (STB_LOCAL)
ffffffff81be7b88-ffffffff81be7c1c: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:620
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_free_page_bad
```
**Symbols:**

```
ffffffff812be8e0-ffffffff812be944: bad_page (STB_LOCAL)
ffffffff81bd9967-ffffffff81bd99fb: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:621
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_free_page_bad
```
**Symbols:**

```
ffffffff81301240-ffffffff813012a4: bad_page (STB_LOCAL)
ffffffff81cbd07a-ffffffff81cbd10e: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:611
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:check_free_page_bad
```
**Symbols:**

```
ffffffff81368860-ffffffff813688e0: bad_page (STB_LOCAL)
ffffffff81e6eeec-ffffffff81e6ef7b: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4370)
Location: mm/page_alloc.c:668
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:free_page_is_bad_report
```
**Symbols:**

```
ffffffff813e4370-ffffffff813e4482: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419000)
Location: mm/page_alloc.c:502
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_page_is_bad_report
```
**Symbols:**

```
ffffffff81419000-ffffffff81419112: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81445bd0)
Location: mm/page_alloc.c:483
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_page_is_bad_report
```
**Symbols:**

```
ffffffff81445bd0-ffffffff81445ce2: bad_page (STB_LOCAL)
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
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010312e58)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffff800010312e58-ffff800010312f74: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052d9a0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
c052d9a0-c052dafc: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e40d0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
c0000000003e40d0-c0000000003e4268: bad_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a098)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffe00021a098-ffffffe00021a1ca: bad_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff81273f60-ffffffff81273fd0: bad_page (STB_LOCAL)
ffffffff8127ae2f-ffffffff8127aee0: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff81265ed0-ffffffff81265f40: bad_page (STB_LOCAL)
ffffffff8126cd0f-ffffffff8126cdc0: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff81271d00-ffffffff81271d70: bad_page (STB_LOCAL)
ffffffff81278bcf-ffffffff81278c80: bad_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void bad_page(struct page *page, const char *reason, long unsigned int bad_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:599
Inline: False
Direct callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:free_pages_check_bad
```
**Symbols:**

```
ffffffff81281760-ffffffff812817d0: bad_page (STB_LOCAL)
ffffffff812887bf-ffffffff81288870: bad_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int bad_flags</code>
</li>
</ul>
</details>
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

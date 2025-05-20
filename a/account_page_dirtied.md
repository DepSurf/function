# Function: <code>account_page_dirtied</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119a810)
Location: mm/page-writeback.c:2406
Inline: False
Direct callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8119a810-ffffffff8119a98f: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811af120)
Location: mm/page-writeback.c:2451
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff811af120-ffffffff811af29e: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bf7c0)
Location: mm/page-writeback.c:2418
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff811bf7c0-ffffffff811bf93e: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7950)
Location: mm/page-writeback.c:2423
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff811c7950-ffffffff811c7b06: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc790)
Location: mm/page-writeback.c:2406
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff811dc790-ffffffff811dc949: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fc780)
Location: mm/page-writeback.c:2407
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff811fc780-ffffffff811fc9e1: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120f2d0)
Location: mm/page-writeback.c:2401
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8120f2d0-ffffffff8120f53d: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81221350)
Location: mm/page-writeback.c:2410
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81221350-ffffffff81221531: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122ede0)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8122ede0-ffffffff8122efe8: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125bec0)
Location: mm/page-writeback.c:2422
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8125bec0-ffffffff8125c0ad: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812662f0)
Location: mm/page-writeback.c:2420
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812662f0-ffffffff8126647c: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126adf0)
Location: mm/page-writeback.c:2420
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8126adf0-ffffffff8126af88: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a4a90)
Location: mm/page-writeback.c:2441
Inline: False
Direct callers:
  - mm/page-writeback.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812a4a90-ffffffff812a4c30: account_page_dirtied (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be050)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffff8000102be050-ffff8000102be28c: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04ea2ec)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
c04ea2ec-c04ea578: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000376e80)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
c000000000376e80-c000000000377194: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e0ac6)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffe0001e0ac6-ffffffe0001e0d5e: account_page_dirtied (STB_GLOBAL)
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
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81227430)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81227430-ffffffff81227638: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a5a0)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8121a5a0-ffffffff8121a7a8: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812251d0)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812251d0-ffffffff812253d8: account_page_dirtied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void account_page_dirtied(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812344b0)
Location: mm/page-writeback.c:2412
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812344b0-ffffffff812346d2: account_page_dirtied (STB_GLOBAL)
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
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
</li>
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

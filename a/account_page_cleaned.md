# Function: <code>account_page_cleaned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct mem_cgroup *memcg, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119b840)
Location: mm/page-writeback.c:2436
Inline: True
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/page-writeback.c:cancel_dirty_page
```
**Symbols:**

```
ffffffff8119b840-ffffffff8119b916: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811b0900)
Location: mm/page-writeback.c:2481
Inline: True
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/page-writeback.c:cancel_dirty_page
```
**Symbols:**

```
ffffffff811b0900-ffffffff811b09dc: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c0ee0)
Location: mm/page-writeback.c:2448
Inline: True
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/page-writeback.c:cancel_dirty_page
```
**Symbols:**

```
ffffffff811c0ee0-ffffffff811c0fbc: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c9100)
Location: mm/page-writeback.c:2452
Inline: True
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/page-writeback.c:cancel_dirty_page
```
**Symbols:**

```
ffffffff811c9100-ffffffff811c91fd: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ddf00)
Location: mm/page-writeback.c:2435
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff811ddf00-ffffffff811ddffd: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ff460)
Location: mm/page-writeback.c:2436
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff811ff460-ffffffff811ff630: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81211d20)
Location: mm/page-writeback.c:2430
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff81211d20-ffffffff81211efc: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812216f0)
Location: mm/page-writeback.c:2438
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff812216f0-ffffffff81221834: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122f1a0)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff8122f1a0-ffffffff8122f2e4: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125c260)
Location: mm/page-writeback.c:2452
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff8125c260-ffffffff8125c398: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81266630)
Location: mm/page-writeback.c:2450
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff81266630-ffffffff8126670a: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126b130)
Location: mm/page-writeback.c:2450
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff8126b130-ffffffff8126b212: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a7c10)
Location: mm/page-writeback.c:2472
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff812a7c10-ffffffff812a7cf9: account_page_cleaned (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be4e8)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffff8000102be4e8-ffff8000102be644: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (c04e73e4)
Location: mm/page-writeback.c:2442
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
c04e7208-c04e7310: account_page_cleaned.part.0 (STB_LOCAL)
c04ea738-c04ea7c8: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (c000000000375120)
Location: mm/page-writeback.c:2442
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
c000000000374e80-c000000000374fc8: account_page_cleaned.part.0 (STB_LOCAL)
c000000000377480-c00000000037753c: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffe0001df75a)
Location: mm/page-writeback.c:2442
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffe0001df59a-ffffffe0001df6ac: account_page_cleaned.part.0 (STB_LOCAL)
ffffffe0001e0edc-ffffffe0001e0f52: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812277f0)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff812277f0-ffffffff81227934: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a960)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff8121a960-ffffffff8121aa90: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81225590)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff81225590-ffffffff812256d4: account_page_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void account_page_cleaned(struct page *page, struct address_space *mapping, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81234890)
Location: mm/page-writeback.c:2442
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page-writeback.c:__cancel_dirty_page
```
**Symbols:**

```
ffffffff81234890-ffffffff812349d4: account_page_cleaned (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>page, mapping, memcg, wb</code> ➡️ <code>page, mapping, wb</code>
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

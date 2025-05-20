# Function: <code>unpin_user_page_range_dirty_lock</code>

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
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297290)
Location: mm/gup.c:380
Inline: False
```
**Symbols:**

```
ffffffff81297290-ffffffff81297404: unpin_user_page_range_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7c40)
Location: mm/gup.c:392
Inline: False
```
**Symbols:**

```
ffffffff812d7c40-ffffffff812d7db4: unpin_user_page_range_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337510)
Location: mm/gup.c:365
Inline: False
```
**Symbols:**

```
ffffffff81337510-ffffffff81337690: unpin_user_page_range_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813ae640)
Location: mm/gup.c:380
Inline: False
```
**Symbols:**

```
ffffffff813ae640-ffffffff813ae777: unpin_user_page_range_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e2f40)
Location: mm/gup.c:424
Inline: False
```
**Symbols:**

```
ffffffff813e2f40-ffffffff813e3077: unpin_user_page_range_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unpin_user_page_range_dirty_lock(struct page *page, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140d780)
Location: mm/gup.c:424
Inline: False
```
**Symbols:**

```
ffffffff8140d780-ffffffff8140d8ae: unpin_user_page_range_dirty_lock (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

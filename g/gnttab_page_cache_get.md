# Function: <code>gnttab_page_cache_get</code>

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
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172f850)
Location: drivers/xen/grant-table.c:877
Inline: False
```
**Symbols:**

```
ffffffff8172f850-ffffffff8172f8b3: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817131e0)
Location: drivers/xen/grant-table.c:877
Inline: False
```
**Symbols:**

```
ffffffff817131e0-ffffffff81713243: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178fe30)
Location: drivers/xen/grant-table.c:884
Inline: False
```
**Symbols:**

```
ffffffff8178fe30-ffffffff8178fe93: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c99e0)
Location: drivers/xen/grant-table.c:950
Inline: False
```
**Symbols:**

```
ffffffff818c99e0-ffffffff818c9a50: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1a8e0)
Location: drivers/xen/grant-table.c:950
Inline: False
```
**Symbols:**

```
ffffffff81a1a8e0-ffffffff81a1a950: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a63a90)
Location: drivers/xen/grant-table.c:968
Inline: False
```
**Symbols:**

```
ffffffff81a63a90-ffffffff81a63b00: gnttab_page_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_page_cache_get(struct gnttab_page_cache *cache, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab62d0)
Location: drivers/xen/grant-table.c:966
Inline: False
```
**Symbols:**

```
ffffffff81ab62d0-ffffffff81ab6340: gnttab_page_cache_get (STB_GLOBAL)
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

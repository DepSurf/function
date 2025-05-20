# Function: <code>kmalloc_cache_name</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123222b)
Location: mm/slab_common.c:1137
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8123222b-ffffffff8123226f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812426fb)
Location: mm/slab_common.c:1165
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff812426fb-ffffffff8124273f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81250c1b)
Location: mm/slab_common.c:1225
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff81250c1b-ffffffff81250c5f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000114556c8)
Location: mm/slab_common.c:1225
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:1225
Inline: True
Inline callers:
  - mm/slab_common.c:create_kmalloc_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c00000000137e30c)
Location: mm/slab_common.c:1225
Inline: True
Inline callers:
  - mm/slab_common.c:new_kmalloc_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0000146d4)
Location: mm/slab_common.c:1225
Inline: True
Inline callers:
  - mm/slab_common.c:new_kmalloc_cache
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
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124926b)
Location: mm/slab_common.c:1225
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8124926b-ffffffff812492af: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123c21b)
Location: mm/slab_common.c:1225
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8123c21b-ffffffff8123c25f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124700b)
Location: mm/slab_common.c:1225
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8124700b-ffffffff8124704f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *kmalloc_cache_name(const char *prefix, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8125683b)
Location: mm/slab_common.c:1225
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8125683b-ffffffff8125687f: kmalloc_cache_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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

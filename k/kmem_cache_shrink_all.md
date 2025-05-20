# Function: <code>kmem_cache_shrink_all</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81250830)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff81250830-ffffffff812508d1: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127ee90)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff8127ee90-ffffffff8127ef48: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e7918)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffff8000102e7918-ffff8000102e79c8: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050ba28)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
c050ba28-c050bac4: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a9740)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
c0000000003a9740-c0000000003a9834: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fd452)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffe0001fd452-ffffffe0001fd4fa: kmem_cache_shrink_all (STB_GLOBAL)
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
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248e80)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff81248e80-ffffffff81248f21: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123be30)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff8123be30-ffffffff8123bed1: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246c20)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff81246c20-ffffffff81246cc1: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kmem_cache_shrink_all(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81256450)
Location: mm/slab_common.c:1002
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
```
**Symbols:**

```
ffffffff81256450-ffffffff812564f1: kmem_cache_shrink_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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

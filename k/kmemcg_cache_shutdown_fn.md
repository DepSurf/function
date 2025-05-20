# Function: <code>kmemcg_cache_shutdown_fn</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (ffffffff8124273f)
Location: mm/slab_common.c:739
Inline: True
```
**Symbols:**

```
ffffffff81240ee0-ffffffff81240ef8: kmemcg_cache_shutdown_fn (STB_LOCAL)
ffffffff8124273f-ffffffff81242752: kmemcg_cache_shutdown_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124f2e0)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff8124f2e0-ffffffff8124f2f8: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d560)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff8127d560-ffffffff8127d578: kmemcg_cache_shutdown_fn (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e5690)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffff8000102e5690-ffff8000102e56d0: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050a504)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
c050a504-c050a540: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6760)
Location: mm/slab_common.c:740
Inline: False
```
**Symbols:**

```
c0000000003a6760-c0000000003a67a0: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc116)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffe0001fc116-ffffffe0001fc14e: kmemcg_cache_shutdown_fn (STB_LOCAL)
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
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247930)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff81247930-ffffffff81247948: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a8e0)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff8123a8e0-ffffffff8123a8f8: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812456d0)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff812456d0-ffffffff812456e8: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kmemcg_cache_shutdown_fn(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812550e0)
Location: mm/slab_common.c:740
Inline: True
```
**Symbols:**

```
ffffffff812550e0-ffffffff812550f8: kmemcg_cache_shutdown_fn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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

# Function: <code>destroy_memcg_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2d9d)
Location: mm/slab_common.c:165
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:slab_kmem_cache_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cdb02)
Location: mm/slab_common.c:170
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811ddc52)
Location: mm/slab_common.c:170
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e7962)
Location: mm/slab_common.c:178
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fdba2)
Location: mm/slab_common.c:179
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121eed2)
Location: mm/slab_common.c:170
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231eb2)
Location: mm/slab_common.c:170
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81242373)
Location: mm/slab_common.c:179
Inline: True
Inline callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124f300)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8124f300-ffffffff8124f378: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d2e0)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8127d2e0-ffffffff8127d35e: destroy_memcg_params (STB_LOCAL)
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
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e6a70)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffff8000102e6a70-ffff8000102e6b34: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050a540)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
c050a540-c050a604: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a76f0)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
c0000000003a76f0-c0000000003a780c: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc14e)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffe0001fc14e-ffffffe0001fc1e8: destroy_memcg_params (STB_LOCAL)
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
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247950)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff81247950-ffffffff812479c8: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a900)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8123a900-ffffffff8123a978: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812456f0)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812456f0-ffffffff81245768: destroy_memcg_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_memcg_params(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255100)
Location: mm/slab_common.c:179
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff81255100-ffffffff8125518d: destroy_memcg_params (STB_LOCAL)
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

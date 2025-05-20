# Function: <code>shutdown_cache</code>

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
In mm/slab_common.c (ffffffff811b3094)
Location: mm/slab_common.c:450
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811ccd63)
Location: mm/slab_common.c:455
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811dce53)
Location: mm/slab_common.c:461
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e5dc0)
Location: mm/slab_common.c:528
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff811e5dc0-ffffffff811e5ef0: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc000)
Location: mm/slab_common.c:537
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff811fc000-ffffffff811fc130: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d330)
Location: mm/slab_common.c:558
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff8121d330-ffffffff8121d476: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230320)
Location: mm/slab_common.c:585
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff81230320-ffffffff81230466: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240d30)
Location: mm/slab_common.c:600
Inline: True
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff81240d30-ffffffff81240ed8: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124e8b0)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff8124e8b0-ffffffff8124ea09: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d400)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:shutdown_memcg_caches
  - mm/slab_common.c:shutdown_memcg_caches
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff8127d400-ffffffff8127d559: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287f31)
Location: mm/slab_common.c:447
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128d2dd)
Location: mm/slab_common.c:460
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cd107)
Location: mm/slab_common.c:461
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132ba33)
Location: mm/slab_common.c:457
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0da7)
Location: mm/slab_common.c:452
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d4027)
Location: mm/slab_common.c:452
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fed97)
Location: mm/slab_common.c:447
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e4b88)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffff8000102e4b88-ffff8000102e4ca0: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c05098a4)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
c05098a4-c05099a4: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6570)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
c0000000003a6570-c0000000003a6758: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fb7a0)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffe0001fb7a0-ffffffe0001fb88a: shutdown_cache (STB_LOCAL)
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
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246f00)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff81246f00-ffffffff81247059: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81239eb0)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff81239eb0-ffffffff8123a009: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244ca0)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff81244ca0-ffffffff81244df9: shutdown_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81254460)
Location: mm/slab_common.c:601
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmemcg_cache_shutdown_fn
```
**Symbols:**

```
ffffffff81254460-ffffffff812545b9: shutdown_cache (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

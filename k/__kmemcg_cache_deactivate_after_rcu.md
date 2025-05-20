# Function: <code>__kmemcg_cache_deactivate_after_rcu</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129a5c0)
Location: mm/slub.c:4035
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff8129a5c0-ffffffff8129a606: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa480)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812aa480-ffffffff812aa4c6: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df1a0)
Location: mm/slub.c:4130
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812df1a0-ffffffff812df1ec: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
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
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c278)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffff80001034c278-ffff80001034c2e0: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054fe74)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
c054fe74-c054fed0: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042bc30)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
c00000000042bc30-c00000000042bccc: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d416)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffe00023d416-ffffffe00023d47c: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
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
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2a60)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812a2a60-ffffffff812a2aa6: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294530)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff81294530-ffffffff81294576: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0870)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812a0870-ffffffff812a08b6: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kmemcg_cache_deactivate_after_rcu(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b09b0)
Location: mm/slub.c:4053
Inline: False
Direct callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812b09b0-ffffffff812b09f6: __kmemcg_cache_deactivate_after_rcu (STB_GLOBAL)
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

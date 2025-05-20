# Function: <code>init_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e87e0)
Location: mm/slub.c:676
Inline: True
Direct callers:
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff811e87e0-ffffffff811e884a: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81207510)
Location: mm/slub.c:691
Inline: True
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81207510-ffffffff812075a6: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81219620)
Location: mm/slub.c:690
Inline: True
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81219620-ffffffff812196b6: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81224320)
Location: mm/slub.c:692
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81224320-ffffffff812243af: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f980)
Location: mm/slub.c:727
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8123f980-ffffffff8123fa06: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81263000)
Location: mm/slub.c:713
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81263000-ffffffff81263085: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277890)
Location: mm/slub.c:718
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81277890-ffffffff81277915: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81293090)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81293090-ffffffff81293115: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2e10)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a2e10-ffffffff812a2e95: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d74f0)
Location: mm/slub.c:756
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812d74f0-ffffffff812d7575: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e3050)
Location: mm/slub.c:751
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812e3050-ffffffff812e30d5: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea7e0)
Location: mm/slub.c:763
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812ea7e0-ffffffff812ea865: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81332720)
Location: mm/slub.c:884
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81332720-ffffffff813327a5: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a3c30)
Location: mm/slub.c:931
Inline: False
Direct callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:setup_object
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff813a3c30-ffffffff813a3cc1: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81426340)
Location: mm/slub.c:998
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81426340-ffffffff8142640b: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145c9f0)
Location: mm/slub.c:1019
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8145c9f0-ffffffff8145cab7: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457100)
Location: mm/slub.c:1132
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81457100-ffffffff814571c7: init_object (STB_LOCAL)
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
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff8000103430c0)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffff8000103430c0-ffff800010343164: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05485f8)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c05485f8-c05486a0: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004206e0)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c0000000004206e0-c0000000004207d8: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000237740)
Location: mm/slub.c:710
Inline: True
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffe000237740-ffffffe0002377ea: init_object (STB_LOCAL)
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
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b3f0)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8129b3f0-ffffffff8129b475: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128cfb0)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8128cfb0-ffffffff8128d035: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299200)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81299200-ffffffff81299285: init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_object(struct kmem_cache *s, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9020)
Location: mm/slub.c:710
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a9020-ffffffff812a90a5: init_object (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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

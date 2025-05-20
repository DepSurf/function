# Function: <code>free_kmem_cache_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ec070)
Location: mm/slub.c:3174
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff811ec070-ffffffff811ec0cd: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b2e0)
Location: mm/slub.c:3336
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff8120b2e0-ffffffff8120b33d: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d320)
Location: mm/slub.c:3358
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff8121d320-ffffffff8121d37d: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81228ba0)
Location: mm/slub.c:3355
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff81228ba0-ffffffff81228bfe: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81242d60)
Location: mm/slub.c:3368
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff81242d60-ffffffff81242db7: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81268010)
Location: mm/slub.c:3351
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff81268010-ffffffff81268066: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ced0)
Location: mm/slub.c:3401
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff8127ced0-ffffffff8127cf26: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299420)
Location: mm/slub.c:3412
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff81299420-ffffffff81299476: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9290)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff812a9290-ffffffff812a92e6: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812deab2)
Location: mm/slub.c:3480
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__kmem_cache_release
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
In mm/slub.c (ffffffff812eb03f)
Location: mm/slub.c:3567
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:init_kmem_cache_nodes
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
In mm/slub.c (ffffffff812f2b0f)
Location: mm/slub.c:3600
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8133b0f8)
Location: mm/slub.c:3937
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
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
In mm/slub.c (ffffffff813ad4d4)
Location: mm/slub.c:3987
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__kmem_cache_release
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
In mm/slub.c (ffffffff8142dc5a)
Location: mm/slub.c:4267
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
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
In mm/slub.c (ffffffff81462f50)
Location: mm/slub.c:4282
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
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
In mm/slub.c (ffffffff8145f1a0)
Location: mm/slub.c:4886
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
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
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034adb0)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffff80001034adb0-ffff80001034ae20: free_kmem_cache_nodes (STB_LOCAL)
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
In mm/slub.c (c054f564)
Location: mm/slub.c:3422
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042a0d0)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
c00000000042a0d0-c00000000042a178: free_kmem_cache_nodes (STB_LOCAL)
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
In mm/slub.c (ffffffe00023cac0)
Location: mm/slub.c:3422
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
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
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a1870)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff812a1870-ffffffff812a18c6: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81293350)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff81293350-ffffffff812933a6: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f680)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff8129f680-ffffffff8129f6d6: free_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812af7b0)
Location: mm/slub.c:3422
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
```
**Symbols:**

```
ffffffff812af7b0-ffffffff812af806: free_kmem_cache_nodes (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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

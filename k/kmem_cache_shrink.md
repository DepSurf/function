# Function: <code>kmem_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b26c0)
Location: mm/slab_common.c:744
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff811b26c0-ffffffff811b26f2: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc140)
Location: mm/slab_common.c:751
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff811cc140-ffffffff811cc172: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc250)
Location: mm/slab_common.c:780
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff811dc250-ffffffff811dc280: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e61c0)
Location: mm/slab_common.c:851
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff811e61c0-ffffffff811e61f0: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc400)
Location: mm/slab_common.c:860
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff811fc400-ffffffff811fc430: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d560)
Location: mm/slab_common.c:916
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8121d560-ffffffff8121d590: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230550)
Location: mm/slab_common.c:943
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff81230550-ffffffff81230580: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240560)
Location: mm/slab_common.c:970
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff81240560-ffffffff81240594: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124ead0)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8124ead0-ffffffff8124eb04: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127eeab)
Location: mm/slab_common.c:984
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
Direct callers:
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8127cd90-ffffffff8127cdc6: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812879a0)
Location: mm/slab_common.c:521
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff812879a0-ffffffff812879d6: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128cb80)
Location: mm/slab_common.c:529
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8128cb80-ffffffff8128cb90: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cc950)
Location: mm/slab_common.c:533
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff812cc950-ffffffff812cc960: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132b0e0)
Location: mm/slab_common.c:524
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8132b0e0-ffffffff8132b0f6: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0540)
Location: mm/slab_common.c:517
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff813a0540-ffffffff813a0556: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3800)
Location: mm/slab_common.c:517
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff813d3800-ffffffff813d3816: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe200)
Location: mm/slab_common.c:512
Inline: False
Direct callers:
  - mm/slub.c:shrink_store
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff813fe200-ffffffff813fe216: kmem_cache_shrink (STB_GLOBAL)
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
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e4d88)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffff8000102e4d88-ffff8000102e4dcc: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050ba4c)
Location: mm/slab_common.c:984
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
```
**Symbols:**

```
c0509c74-c0509ca8: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6910)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
```
**Symbols:**

```
c0000000003a6910-c0000000003a6974: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fd472)
Location: mm/slab_common.c:984
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
```
**Symbols:**

```
ffffffe0001fb910-ffffffe0001fb93a: kmem_cache_shrink (STB_GLOBAL)
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
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247120)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff81247120-ffffffff81247154: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a0d0)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff8123a0d0-ffffffff8123a104: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244ec0)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff81244ec0-ffffffff81244ef4: kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kmem_cache_shrink(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812548b0)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - drivers/acpi/osl.c:acpi_os_purge_cache
```
**Symbols:**

```
ffffffff812548b0-ffffffff812548e4: kmem_cache_shrink (STB_GLOBAL)
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

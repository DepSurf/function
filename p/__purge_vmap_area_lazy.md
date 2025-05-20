# Function: <code>__purge_vmap_area_lazy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __purge_vmap_area_lazy(long unsigned int *start, long unsigned int *end, int sync, int force_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ccd00)
Location: mm/vmalloc.c:602
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff811ccd00-ffffffff811cd077: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __purge_vmap_area_lazy(long unsigned int *start, long unsigned int *end, int sync, int force_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e9dc0)
Location: mm/vmalloc.c:626
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff811e9dc0-ffffffff811ea0c8: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fad30)
Location: mm/vmalloc.c:626
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff811fad30-ffffffff811fade4: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81205a30)
Location: mm/vmalloc.c:677
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81205a30-ffffffff81205af0: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121e850)
Location: mm/vmalloc.c:675
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8121e850-ffffffff8121e910: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812415a0)
Location: mm/vmalloc.c:655
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812415a0-ffffffff81241660: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255ca0)
Location: mm/vmalloc.c:655
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81255ca0-ffffffff81255d60: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81268d80)
Location: mm/vmalloc.c:1248
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81268d80-ffffffff81268ea1: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812776c0)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812776c0-ffffffff81277d8d: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a8580)
Location: mm/vmalloc.c:1346
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812a8580-ffffffff812a8c63: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b37c0)
Location: mm/vmalloc.c:1337
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812b37c0-ffffffff812b3ea1: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b8ea0)
Location: mm/vmalloc.c:1607
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812b8ea0-ffffffff812b9585: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fb440)
Location: mm/vmalloc.c:1659
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812fb440-ffffffff812fbb25: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81362b30)
Location: mm/vmalloc.c:1677
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff81362b30-ffffffff81363252: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813de500)
Location: mm/vmalloc.c:1730
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff813de500-ffffffff813decdc: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81412f10)
Location: mm/vmalloc.c:1724
Inline: False
Direct callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
**Symbols:**

```
ffffffff81412f10-ffffffff814136b3: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143f980)
Location: mm/vmalloc.c:1724
Inline: False
Direct callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
**Symbols:**

```
ffffffff8143f980-ffffffff81440123: __purge_vmap_area_lazy (STB_LOCAL)
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030db58)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffff80001030db58-ffff80001030e2d0: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c05295b8)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
c05295b8-c0529d50: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003de750)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
c0000000003de750-c0000000003df020: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffe00021684c)
Location: mm/vmalloc.c:1245
Inline: True
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffe00021684c-ffffffe000216d84: __purge_vmap_area_lazy.isra.0 (STB_LOCAL)
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fd10)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8126fd10-ffffffff812703dd: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81261c80)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81261c80-ffffffff8126234d: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126dab0)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8126dab0-ffffffff8126e17d: __purge_vmap_area_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127d470)
Location: mm/vmalloc.c:1245
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8127d470-ffffffff8127db3b: __purge_vmap_area_lazy (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sync</code>
</li>
<li>
<b>Param removed. </b>
<code>int force_flush</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int *start</code> ➡️ <code>long unsigned int start</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int *end</code> ➡️ <code>long unsigned int end</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

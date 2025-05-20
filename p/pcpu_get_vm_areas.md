# Function: <code>pcpu_get_vm_areas</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cd950)
Location: mm/vmalloc.c:2383
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff811cd950-ffffffff811cde9d: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811eb6e0)
Location: mm/vmalloc.c:2404
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff811eb6e0-ffffffff811ebc52: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fc950)
Location: mm/vmalloc.c:2417
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff811fc950-ffffffff811fce8e: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207630)
Location: mm/vmalloc.c:2487
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81207630-ffffffff81207ba6: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220720)
Location: mm/vmalloc.c:2483
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81220720-ffffffff81220ca0: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242510)
Location: mm/vmalloc.c:2470
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81242510-ffffffff81242b3b: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81256c40)
Location: mm/vmalloc.c:2472
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81256c40-ffffffff81257280: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3206
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff8126bbdf-ffffffff8126bc0d: pcpu_get_vm_areas.cold (STB_LOCAL)
ffffffff8126aeb0-ffffffff8126bab8: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279de0)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81279de0-ffffffff8127a9ba: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812aa590)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812aa590-ffffffff812ab65f: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b5c60)
Location: mm/vmalloc.c:3203
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812b5c60-ffffffff812b6bb1: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bb350)
Location: mm/vmalloc.c:3455
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812bb350-ffffffff812bc29c: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fd980)
Location: mm/vmalloc.c:3566
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812fd980-ffffffff812fe8c7: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81364900)
Location: mm/vmalloc.c:3728
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81364900-ffffffff813659ad: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e0460)
Location: mm/vmalloc.c:3790
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff813e0460-ffffffff813e14a1: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81415220)
Location: mm/vmalloc.c:4023
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81415220-ffffffff81416213: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81441cf0)
Location: mm/vmalloc.c:4023
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81441cf0-ffffffff81442ceb: pcpu_get_vm_areas (STB_GLOBAL)
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
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103110a8)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffff8000103110a8-ffff800010311d68: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a9c8)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
c052a9c8-c052b6e4: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1f40)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
c0000000003e1f40-c0000000003e2d8c: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000218d4c)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffe000218d4c-ffffffe0002196fc: pcpu_get_vm_areas (STB_GLOBAL)
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
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81272430)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81272430-ffffffff8127300a: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812643a0)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812643a0-ffffffff81264f7a: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812701d0)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812701d0-ffffffff81270daa: pcpu_get_vm_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_struct **pcpu_get_vm_areas(const long unsigned int *offsets, const size_t *sizes, int nr_vms, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127fc00)
Location: mm/vmalloc.c:3217
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff8127fc00-ffffffff81280811: pcpu_get_vm_areas (STB_GLOBAL)
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

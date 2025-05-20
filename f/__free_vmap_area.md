# Function: <code>__free_vmap_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc8e0)
Location: mm/vmalloc.c:479
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811cc8e0-ffffffff811cc9c1: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e99a0)
Location: mm/vmalloc.c:504
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff811e99a0-ffffffff811e9a83: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fac40)
Location: mm/vmalloc.c:504
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff811fac40-ffffffff811fad23: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81205940)
Location: mm/vmalloc.c:555
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81205940-ffffffff81205a23: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121e760)
Location: mm/vmalloc.c:553
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8121e760-ffffffff8121e843: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81240530)
Location: mm/vmalloc.c:553
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81240530-ffffffff81240613: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81254e30)
Location: mm/vmalloc.c:553
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81254e30-ffffffff81254f13: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1167
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81268000-ffffffff812685fd: __free_vmap_area (STB_LOCAL)
ffffffff8126bb51-ffffffff8126bb77: __free_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81276950)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81276950-ffffffff81276f52: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030ce28)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffff80001030ce28-ffff80001030d488: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0528968)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c0528968-c0528fb0: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dd670)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c0000000003dd670-c0000000003ddea4: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215dfc)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffe000215dfc-ffffffe000216266: __free_vmap_area (STB_LOCAL)
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
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126efa0)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8126efa0-ffffffff8126f5a2: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260f10)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81260f10-ffffffff81261512: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126cd40)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8126cd40-ffffffff8126d342: __free_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_vmap_area(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127c6d0)
Location: mm/vmalloc.c:1164
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8127c6d0-ffffffff8127ccd2: __free_vmap_area (STB_LOCAL)
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

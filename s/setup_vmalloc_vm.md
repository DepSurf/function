# Function: <code>setup_vmalloc_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc710)
Location: mm/vmalloc.c:1306
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff811cc710-ffffffff811cc776: setup_vmalloc_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e9780)
Location: mm/vmalloc.c:1330
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
**Symbols:**

```
ffffffff811e9780-ffffffff811e97e6: setup_vmalloc_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811faac0)
Location: mm/vmalloc.c:1313
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
**Symbols:**

```
ffffffff811faac0-ffffffff811fab26: setup_vmalloc_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81205630)
Location: mm/vmalloc.c:1364
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
**Symbols:**

```
ffffffff81205630-ffffffff81205696: setup_vmalloc_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121e5e0)
Location: mm/vmalloc.c:1362
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
**Symbols:**

```
ffffffff8121e5e0-ffffffff8121e646: setup_vmalloc_vm (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff81242aa3)
Location: mm/vmalloc.c:1349
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff812571e9)
Location: mm/vmalloc.c:1350
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff8126b96e)
Location: mm/vmalloc.c:2011
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127a837)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff812aa149)
Location: mm/vmalloc.c:2072
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff812b5289)
Location: mm/vmalloc.c:2054
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff812ba676)
Location: mm/vmalloc.c:2327
Inline: True
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
In mm/vmalloc.c (ffffffff812fcc76)
Location: mm/vmalloc.c:2379
Inline: True
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
In mm/vmalloc.c (ffffffff81363e48)
Location: mm/vmalloc.c:2409
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff813dff58)
Location: mm/vmalloc.c:2471
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff81414c9c)
Location: mm/vmalloc.c:2551
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffff8144173b)
Location: mm/vmalloc.c:2551
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff800010311c80)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void setup_vmalloc_vm(struct vm_struct *vm, struct vmap_area *va, long unsigned int flags, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0527c00)
Location: mm/vmalloc.c:2018
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
**Symbols:**

```
c0527c00-c0527c74: setup_vmalloc_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e2878)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
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
In mm/vmalloc.c (ffffffe000219392)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81272e87)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81264df7)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270c27)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81280734)
Location: mm/vmalloc.c:2018
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
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
</ul>
<b>Arch</b>
<ul>
</ul>

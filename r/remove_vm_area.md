# Function: <code>remove_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cec80)
Location: mm/vmalloc.c:1430
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff811cec80-ffffffff811cecec: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ebe20)
Location: mm/vmalloc.c:1454
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff811ebe20-ffffffff811ebe8e: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd050)
Location: mm/vmalloc.c:1437
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff811fd050-ffffffff811fd0c9: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207d40)
Location: mm/vmalloc.c:1488
Inline: False
```
**Symbols:**

```
ffffffff81207d40-ffffffff81207dc7: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220e30)
Location: mm/vmalloc.c:1486
Inline: False
```
**Symbols:**

```
ffffffff81220e30-ffffffff81220eb7: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242cd0)
Location: mm/vmalloc.c:1473
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81242cd0-ffffffff81242d5a: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812573b0)
Location: mm/vmalloc.c:1475
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812573b0-ffffffff8125743a: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81269310)
Location: mm/vmalloc.c:2142
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81269310-ffffffff812693a2: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81278240)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81278240-ffffffff812782e4: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812abca0)
Location: mm/vmalloc.c:2193
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812abca0-ffffffff812abd47: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b71c0)
Location: mm/vmalloc.c:2175
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812b71c0-ffffffff812b726e: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bca90)
Location: mm/vmalloc.c:2451
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812bca90-ffffffff812bcb3b: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff220)
Location: mm/vmalloc.c:2503
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812ff220-ffffffff812ff2cb: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366240)
Location: mm/vmalloc.c:2543
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81366240-ffffffff813662f7: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e1e40)
Location: mm/vmalloc.c:2605
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff813e1e40-ffffffff813e1ef7: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416b80)
Location: mm/vmalloc.c:2685
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
ffffffff81416b80-ffffffff81416bfd: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443650)
Location: mm/vmalloc.c:2685
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
```
**Symbols:**

```
ffffffff81443650-ffffffff814436cd: remove_vm_area (STB_GLOBAL)
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
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030e980)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffff80001030e980-ffff80001030ea98: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a334)
Location: mm/vmalloc.c:2148
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
c052a334-c052a3f8: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003df8e0)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:free_vm_area
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
c0000000003df8e0-c0000000003dfa64: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000217334)
Location: mm/vmalloc.c:2148
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffe000217334-ffffffe000217456: remove_vm_area (STB_GLOBAL)
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
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270890)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81270890-ffffffff81270934: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262800)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81262800-ffffffff812628a4: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e630)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8126e630-ffffffff8126e6d4: remove_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_struct *remove_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e000)
Location: mm/vmalloc.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8127e000-ffffffff8127e0a2: remove_vm_area (STB_GLOBAL)
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

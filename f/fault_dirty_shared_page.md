# Function: <code>fault_dirty_shared_page</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811e6450)
Location: mm/memory.c:2067
Inline: True
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811e6450-ffffffff811e64f9: fault_dirty_shared_page.isra.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811f14e0)
Location: mm/memory.c:2273
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811f14e0-ffffffff811f1577: fault_dirty_shared_page.isra.67 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812081b0)
Location: mm/memory.c:2390
Inline: True
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812081b0-ffffffff81208247: fault_dirty_shared_page.isra.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81229130)
Location: mm/memory.c:2432
Inline: True
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81229130-ffffffff812291c7: fault_dirty_shared_page.isra.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8123c7c0)
Location: mm/memory.c:2168
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8123c7c0-ffffffff8123c857: fault_dirty_shared_page.isra.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8124e010)
Location: mm/memory.c:2222
Inline: True
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8124e010-ffffffff8124e0a6: fault_dirty_shared_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125c540)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8125c540-ffffffff8125c61c: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128bac0)
Location: mm/memory.c:2560
Inline: False
Direct callers:
  - mm/memory.c:do_shared_fault
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff8128bac0-ffffffff8128bbae: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81296a70)
Location: mm/memory.c:2737
Inline: False
Direct callers:
  - mm/memory.c:do_shared_fault
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff81296a70-ffffffff81296b7e: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129c610)
Location: mm/memory.c:2798
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8129c610-ffffffff8129c717: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dd290)
Location: mm/memory.c:2893
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812dd290-ffffffff812dd38c: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133cf70)
Location: mm/memory.c:2986
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8133cf70-ffffffff8133d0a3: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b4b50)
Location: mm/memory.c:2966
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813b4b50-ffffffff813b4c7a: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813e9b50)
Location: mm/memory.c:2965
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813e9b50-ffffffff813e9c83: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81414cb0)
Location: mm/memory.c:2989
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81414cb0-ffffffff81414df7: fault_dirty_shared_page (STB_LOCAL)
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
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4a30)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffff8000102f4a30-ffff8000102f4b40: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051670c)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c051670c-c051681c: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003ba950)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0000000003ba950-c0000000003baac8: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000205bda)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe000205bda-ffffffe000205ccc: fault_dirty_shared_page (STB_LOCAL)
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
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254b90)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81254b90-ffffffff81254c6c: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812479d0)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812479d0-ffffffff81247aac: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252930)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81252930-ffffffff81252a0c: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t fault_dirty_shared_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262300)
Location: mm/memory.c:2231
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81262300-ffffffff812623dc: fault_dirty_shared_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

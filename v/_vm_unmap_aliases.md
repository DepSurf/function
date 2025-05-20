# Function: <code>_vm_unmap_aliases</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812693e0)
Location: mm/vmalloc.c:1661
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812693e0-ffffffff81269506: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81278320)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81278320-ffffffff81278446: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812abe96)
Location: mm/vmalloc.c:1768
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812a8f90-ffffffff812a90cb: _vm_unmap_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812b73b6)
Location: mm/vmalloc.c:1750
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812b43e0-ffffffff812b4524: _vm_unmap_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812bcc86)
Location: mm/vmalloc.c:2020
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812b9ac0-ffffffff812b9c07: _vm_unmap_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812fc0bd)
Location: mm/vmalloc.c:2072
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812fc080-ffffffff812fc215: _vm_unmap_aliases (STB_LOCAL)
ffffffff81cbced4-ffffffff81cbcee8: _vm_unmap_aliases.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff8136329d)
Location: mm/vmalloc.c:2090
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81363260-ffffffff813633e0: _vm_unmap_aliases (STB_LOCAL)
ffffffff81e6eb7f-ffffffff81e6eb93: _vm_unmap_aliases.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff813ded2d)
Location: mm/vmalloc.c:2152
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff813decf0-ffffffff813dee78: _vm_unmap_aliases (STB_LOCAL)
ffffffff82064a8d-ffffffff82064aa1: _vm_unmap_aliases.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2259
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vm_unmap_aliases
```
**Symbols:**

```
ffffffff814139a0-ffffffff81413ca5: _vm_unmap_aliases (STB_LOCAL)
ffffffff820e4192-ffffffff820e41a6: _vm_unmap_aliases.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2259
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_aliases
```
**Symbols:**

```
ffffffff81440410-ffffffff81440715: _vm_unmap_aliases (STB_LOCAL)
ffffffff821c0dc6-ffffffff821c0dda: _vm_unmap_aliases.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030ead8)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffff80001030ead8-ffff80001030ece8: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a42c)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
c052a42c-c052a594: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dfad0)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
c0000000003dfad0-c0000000003dfd04: _vm_unmap_aliases (STB_LOCAL)
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
In mm/vmalloc.c (ffffffe00021748e)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffe00021748e-ffffffe0002175f0: _vm_unmap_aliases.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270970)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff81270970-ffffffff81270a96: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812628e0)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff812628e0-ffffffff81262a06: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e710)
Location: mm/vmalloc.c:1669
Inline: True
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8126e710-ffffffff8126e836: _vm_unmap_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e34f)
Location: mm/vmalloc.c:1669
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
Direct callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
**Symbols:**

```
ffffffff8127e0e0-ffffffff8127e202: _vm_unmap_aliases.part.0 (STB_LOCAL)
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
</ul>

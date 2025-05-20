# Function: <code>vm_lock_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c835e)
Location: mm/mmap.c:3163
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811e0350)
Location: mm/mmap.c:3137
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff811e0350-ffffffff811e037a: vm_lock_mapping.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811f02a0)
Location: mm/mmap.c:3298
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff811f02a0-ffffffff811f02c7: vm_lock_mapping.isra.26 (STB_LOCAL)
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
In mm/mmap.c (ffffffff811fb120)
Location: mm/mmap.c:3355
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff811fb120-ffffffff811fb147: vm_lock_mapping.isra.27 (STB_LOCAL)
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
In mm/mmap.c (ffffffff81213640)
Location: mm/mmap.c:3398
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81213640-ffffffff81213668: vm_lock_mapping.isra.25 (STB_LOCAL)
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
In mm/mmap.c (ffffffff81234740)
Location: mm/mmap.c:3453
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81234740-ffffffff81234768: vm_lock_mapping.isra.30 (STB_LOCAL)
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
In mm/mmap.c (ffffffff81247ec0)
Location: mm/mmap.c:3497
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81247ec0-ffffffff81247ee8: vm_lock_mapping.isra.25 (STB_LOCAL)
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
In mm/mmap.c (ffffffff8125a0e0)
Location: mm/mmap.c:3503
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff8125a0e0-ffffffff8125a108: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81268590)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81268590-ffffffff812685b8: vm_lock_mapping.isra.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffff81298b50)
Location: mm/mmap.c:3523
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81298b50-ffffffff81298b78: vm_lock_mapping.constprop.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffff812a3cd0)
Location: mm/mmap.c:3597
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff812a3cd0-ffffffff812a3cf8: vm_lock_mapping.constprop.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffff812a9460)
Location: mm/mmap.c:3564
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff812a9460-ffffffff812a9488: vm_lock_mapping.constprop.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffff812ef62e)
Location: mm/mmap.c:3544
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
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
In mm/mmap.c (ffffffff81352aa6)
Location: mm/mmap.c:3538
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff813c6b70)
Location: mm/mmap.c:3500
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff813c6b70-ffffffff813c6bae: vm_lock_mapping.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff813fb000)
Location: mm/mmap.c:3595
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff813fb000-ffffffff813fb038: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81426c50)
Location: mm/mmap.c:3680
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81426c50-ffffffff81426c88: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffff8000102ffe80)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffff8000102ffe80-ffff8000102fff14: vm_lock_mapping.isra.0 (STB_LOCAL)
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
In mm/mmap.c (c0522c54)
Location: mm/mmap.c:3509
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (c0000000003cb6c0)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
c0000000003cb6c0-c0000000003cb730: vm_lock_mapping.isra.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffe00020d714)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffe00020d714-ffffffe00020d758: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81260be0)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81260be0-ffffffff81260c08: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81253000)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff81253000-ffffffff81253028: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8125e980)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff8125e980-ffffffff8125e9a8: vm_lock_mapping.isra.0 (STB_LOCAL)
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
In mm/mmap.c (ffffffff8126e350)
Location: mm/mmap.c:3509
Inline: True
Direct callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
**Symbols:**

```
ffffffff8126e350-ffffffff8126e378: vm_lock_mapping.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

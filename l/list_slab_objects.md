# Function: <code>list_slab_objects</code>

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
In mm/slub.c (ffffffff811edf9d)
Location: mm/slub.c:3416
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120d4a0)
Location: mm/slub.c:3599
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121f500)
Location: mm/slub.c:3621
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122ac50)
Location: mm/slub.c:3625
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81246350)
Location: mm/slub.c:3641
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8126993f)
Location: mm/slub.c:3620
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8127e20b)
Location: mm/slub.c:3673
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81299f91)
Location: mm/slub.c:3680
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a9e51)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812dfd58)
Location: mm/slub.c:3768
Inline: True
Direct callers:
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff812dfd58-ffffffff812dfe4b: list_slab_objects.constprop.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81be951c)
Location: mm/slub.c:3856
Inline: True
Direct callers:
  - mm/slub.c:free_partial
```
**Symbols:**

```
ffffffff81be951c-ffffffff81be9614: list_slab_objects.constprop.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81bdba3d)
Location: mm/slub.c:3883
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81cc1c36)
Location: mm/slub.c:4220
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81e740fd)
Location: mm/slub.c:4257
Inline: True
Inline callers:
  - mm/slub.c:free_partial
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
In mm/slub.c (ffffffff8142ce92)
Location: mm/slub.c:4545
Inline: True
Inline callers:
  - mm/slub.c:free_partial
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
In mm/slub.c (ffffffff814624a2)
Location: mm/slub.c:4560
Inline: True
Inline callers:
  - mm/slub.c:free_partial
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
In mm/slub.c (ffffffff8145e9d0)
Location: mm/slub.c:5164
Inline: True
Inline callers:
  - mm/slub.c:free_partial
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
In mm/slub.c (ffff80001034ba18)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c054f8dc)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c00000000042b14c)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffe00023ce4e)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a2431)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81293f0c)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a0241)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812b0381)
Location: mm/slub.c:3690
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
</ul>

## Differences

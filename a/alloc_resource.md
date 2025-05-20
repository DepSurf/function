# Function: <code>alloc_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086a00)
Location: kernel/resource.c:188
Inline: True
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:release_mem_region_adjustable
```
**Symbols:**

```
ffffffff81086a00-ffffffff81086aa6: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089a50)
Location: kernel/resource.c:197
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff81089a50-ffffffff81089af6: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e9a0)
Location: kernel/resource.c:197
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8108e9a0-ffffffff8108ea46: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b970)
Location: kernel/resource.c:197
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8108b970-ffffffff8108ba02: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810926f0)
Location: kernel/resource.c:197
Inline: False
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810926f0-ffffffff81092782: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810960b0)
Location: kernel/resource.c:164
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810960b0-ffffffff81096142: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e420)
Location: kernel/resource.c:164
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8109e420-ffffffff8109e4b2: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a29a0)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a29a0-ffffffff810a2a52: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8f70)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a8f70-ffffffff810a9022: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0480)
Location: kernel/resource.c:165
Inline: False
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:__reserve_region_with_split
```
**Symbols:**

```
ffffffff810b0480-ffffffff810b0518: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810abba0)
Location: kernel/resource.c:165
Inline: False
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:__reserve_region_with_split
```
**Symbols:**

```
ffffffff810abba0-ffffffff810abc38: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad270)
Location: kernel/resource.c:164
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810ad270-ffffffff810ad308: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bede0)
Location: kernel/resource.c:164
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810bede0-ffffffff810bee78: alloc_resource (STB_LOCAL)
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
In kernel/resource.c (ffffffff810d6145)
Location: kernel/resource.c:165
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff810f5806)
Location: kernel/resource.c:165
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff81101c46)
Location: kernel/resource.c:165
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff8110b3a7)
Location: kernel/resource.c:165
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
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
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000100fff90)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffff8000100fff90-ffff800010100070: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035cff0)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
c035cff0-c035d088: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void alloc_resource(struct pci_dev *dev, int idx);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c000000001352558)
Location: arch/powerpc/kernel/pci-common.c:1231
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
```
```
In kernel/resource.c (c000000000148130)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
c000000000148130-c000000000148240: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7f4a)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffe0000c7f4a-ffffffe0000c8006: alloc_resource (STB_LOCAL)
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
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2890)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a2890-ffffffff810a2942: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091270)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff81091270-ffffffff81091322: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2840)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a2840-ffffffff810a28f2: alloc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct resource *alloc_resource(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa8b0)
Location: kernel/resource.c:165
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810aa8b0-ffffffff810aa975: alloc_resource (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *dev</code>
</li>
<li>
<b>Param added. </b>
<code>int idx</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct resource *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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

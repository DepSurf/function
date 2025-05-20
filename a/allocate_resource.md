# Function: <code>allocate_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810873a0)
Location: kernel/resource.c:693
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff810873a0-ffffffff810875e6: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108a440)
Location: kernel/resource.c:724
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8108a440-ffffffff8108a51b: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108f390)
Location: kernel/resource.c:724
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8108f390-ffffffff8108f46b: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108c330)
Location: kernel/resource.c:724
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8108c330-ffffffff8108c414: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81093070)
Location: kernel/resource.c:742
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81093070-ffffffff81093154: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096aa0)
Location: kernel/resource.c:711
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81096aa0-ffffffff81096b76: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109edc0)
Location: kernel/resource.c:705
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8109edc0-ffffffff8109ee96: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a33f0)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff810a33f0-ffffffff810a34c9: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9a20)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff810a9a20-ffffffff810a9af9: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b15e0)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:additional_memory_resource
```
**Symbols:**

```
ffffffff810b15e0-ffffffff810b16b9: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acd40)
Location: kernel/resource.c:726
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810acd40-ffffffff810ace19: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810adf20)
Location: kernel/resource.c:718
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810adf20-ffffffff810adff5: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bfaa0)
Location: kernel/resource.c:718
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810bfaa0-ffffffff810bfb75: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6f30)
Location: kernel/resource.c:705
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810d6f30-ffffffff810d701a: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6990)
Location: kernel/resource.c:706
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810f6990-ffffffff810f6a7a: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81102da0)
Location: kernel/resource.c:706
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81102da0-ffffffff81102e8a: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110c6d0)
Location: kernel/resource.c:761
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff8110c6d0-ffffffff8110c7ba: allocate_resource (STB_GLOBAL)
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
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101860)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffff800010101860-ffff8000101019c4: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035dc4c)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_resource
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
```
**Symbols:**

```
c035dc4c-c035dea4: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001490b0)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
```
**Symbols:**

```
c0000000001490b0-c0000000001491e4: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8a88)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
```
**Symbols:**

```
ffffffe0000c8a88-ffffffe0000c8b58: allocate_resource (STB_GLOBAL)
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
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3340)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
```
**Symbols:**

```
ffffffff810a3340-ffffffff810a3419: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091d20)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
```
**Symbols:**

```
ffffffff81091d20-ffffffff81091df9: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a32f0)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff810a32f0-ffffffff810a33c9: allocate_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int allocate_resource(struct resource *root, struct resource *new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab390)
Location: kernel/resource.c:719
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff810ab390-ffffffff810ab46e: allocate_resource (STB_GLOBAL)
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

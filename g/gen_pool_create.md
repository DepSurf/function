# Function: <code>gen_pool_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81406f20)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff81406f20-ffffffff81406f74: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144ecb0)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff8144ecb0-ffffffff8144ed04: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146d670)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff8146d670-ffffffff8146d6c4: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81472d40)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff81472d40-ffffffff81472d94: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a00c0)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff814a00c0-ffffffff814a0114: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d5270)
Location: lib/genalloc.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_init
```
**Symbols:**

```
ffffffff814d5270-ffffffff814d52c4: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814e9cc0)
Location: lib/genalloc.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff814e9cc0-ffffffff814e9d14: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815168f0)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff815168f0-ffffffff81516944: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537330)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff81537330-ffffffff81537384: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159b7e0)
Location: lib/genalloc.c:151
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff8159b7e0-ffffffff8159b837: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7080)
Location: lib/genalloc.c:152
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff815b7080-ffffffff815b70d7: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c1ef0)
Location: lib/genalloc.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff815c1ef0-ffffffff815c1f47: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81629d60)
Location: lib/genalloc.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff81629d60-ffffffff81629db7: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff816fb020)
Location: lib/genalloc.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff816fb020-ffffffff816fb083: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff817edb90)
Location: lib/genalloc.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff817edb90-ffffffff817edbf3: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8182dfa0)
Location: lib/genalloc.c:151
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff8182dfa0-ffffffff8182e003: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8187fb30)
Location: lib/genalloc.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff8187fb30-ffffffff8187fbc2: gen_pool_create (STB_GLOBAL)
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
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010643d28)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
**Symbols:**

```
ffff800010643d28-ffff800010643d84: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07ea448)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:atomic_pool_init
```
**Symbols:**

```
c07ea448-c07ea4a8: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007ef730)
Location: lib/genalloc.c:151
Inline: False
```
**Symbols:**

```
c0000000007ef730-c0000000007ef7b8: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe0004707a6)
Location: lib/genalloc.c:151
Inline: False
```
**Symbols:**

```
ffffffe0004707a6-ffffffe0004707f8: gen_pool_create (STB_GLOBAL)
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
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152f910)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff8152f910-ffffffff8152f964: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8151fbf0)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
**Symbols:**

```
ffffffff8151fbf0-ffffffff8151fc44: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152b650)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff8152b650-ffffffff8152b6a4: gen_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gen_pool *gen_pool_create(int min_alloc_order, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815452a0)
Location: lib/genalloc.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff815452a0-ffffffff815452f4: gen_pool_create (STB_GLOBAL)
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

# Function: <code>dma_contiguous_reserve_area</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma **res_cma, bool fixed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffff8000114476d4)
Location: kernel/dma/contiguous.c:162
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_contiguous_reserve
```
**Symbols:**

```
ffff8000114476d4-ffff80001144775c: dma_contiguous_reserve_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma **res_cma, bool fixed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (c1521d60)
Location: kernel/dma/contiguous.c:162
Inline: False
Direct callers:
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_reserve
  - kernel/dma/contiguous.c:dma_contiguous_reserve
```
**Symbols:**

```
c1521d60-c1521de4: dma_contiguous_reserve_area (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma **res_cma, bool fixed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffe00000900e)
Location: kernel/dma/contiguous.c:162
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_contiguous_reserve
```
**Symbols:**

```
ffffffe00000900e-ffffffe00000907e: dma_contiguous_reserve_area (STB_GLOBAL)
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
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma **res_cma, bool fixed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffff828b8ae8)
Location: kernel/dma/contiguous.c:162
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_contiguous_reserve
```
**Symbols:**

```
ffffffff828b8ae8-ffffffff828b8b39: dma_contiguous_reserve_area (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>

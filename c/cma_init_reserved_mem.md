# Function: <code>cma_init_reserved_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff81f8e4b7)
Location: mm/cma.c:169
Inline: True
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81f8e4b7-ffffffff81f8e587: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff81fb8aa9)
Location: mm/cma.c:169
Inline: True
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81fb8aa9-ffffffff81fb8b7a: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff81ff541a)
Location: mm/cma.c:169
Inline: True
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81ff541a-ffffffff81ff54eb: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff820d7b77)
Location: mm/cma.c:172
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff820d7b77-ffffffff820d7c99: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff826e080b)
Location: mm/cma.c:172
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff826e080b-ffffffff826e092d: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8270ad28)
Location: mm/cma.c:176
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff8270ad28-ffffffff8270ae4a: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828c1f0c)
Location: mm/cma.c:176
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828c1f0c-ffffffff828c202e: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828db2d2)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828db2d2-ffffffff828db3f3: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828e3708)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828e3708-ffffffff828e3829: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
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
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffff80001145cc64)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:rmem_cma_setup
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffff80001145cc64-ffff80001145cdc0: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c1534f80)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:rmem_cma_setup
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
c1534f80-c15350b8: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c0000000013872cc)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_cma_init
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
c0000000013872cc-c00000000138748c: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffe000019c9c)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:rmem_cma_setup
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffe000019c9c-ffffffe000019dca: cma_init_reserved_mem (STB_GLOBAL)
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
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828cc5bc)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828cc5bc-ffffffff828cc6dd: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828c4cd8)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828c4cd8-ffffffff828c4df9: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828df33c)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828df33c-ffffffff828df45d: cma_init_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cma_init_reserved_mem(phys_addr_t base, phys_addr_t size, unsigned int order_per_bit, const char *name, struct cma **res_cma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff828e4753)
Location: mm/cma.c:174
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828e4753-ffffffff828e4874: cma_init_reserved_mem (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param reordered. </b>
<code>base, size, order_per_bit, res_cma</code> ➡️ <code>base, size, order_per_bit, name, res_cma</code>
</li>
</ul>
</details>
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

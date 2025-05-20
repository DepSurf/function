# Function: <code>early_init_dt_alloc_reserved_memory_arch</code>

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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t *res_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffff8000114ac374)
Location: drivers/of/of_reserved_mem.c:29
Inline: False
Direct callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffff8000114ac374-ffff8000114ac404: early_init_dt_alloc_reserved_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t *res_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c15b0a8c)
Location: drivers/of/of_reserved_mem.c:29
Inline: False
Direct callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c15b0a8c-c15b0afc: early_init_dt_alloc_reserved_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t *res_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c0000000013bc7a8)
Location: drivers/of/of_reserved_mem.c:29
Inline: False
Direct callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c0000000013bc7a8-c0000000013bc864: early_init_dt_alloc_reserved_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t *res_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffffffe00003c4f4)
Location: drivers/of/of_reserved_mem.c:29
Inline: False
Direct callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe00003c4f4-ffffffe00003c576: early_init_dt_alloc_reserved_memory_arch (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
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

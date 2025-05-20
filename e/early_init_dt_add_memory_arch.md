# Function: <code>early_init_dt_add_memory_arch</code>

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
void early_init_dt_add_memory_arch(u64 base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab050)
Location: drivers/of/fdt.c:1106
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_scan_memory
```
**Symbols:**

```
ffff8000114ab050-ffff8000114ab0c4: early_init_dt_add_memory_arch (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void early_init_dt_add_memory_arch(u64 base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15af5c4)
Location: drivers/of/fdt.c:1106
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_scan_memory
```
**Symbols:**

```
c15af5c4-c15af7bc: early_init_dt_add_memory_arch (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void early_init_dt_add_memory_arch(u64 base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/prom.c (c00000000134997c)
Location: arch/powerpc/kernel/prom.c:554
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_memory
```
**Symbols:**

```
c00000000134997c-c000000001349a38: early_init_dt_add_memory_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void early_init_dt_add_memory_arch(u64 base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b360)
Location: drivers/of/fdt.c:1106
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_memory
```
**Symbols:**

```
ffffffe00003b360-ffffffe00003b428: early_init_dt_add_memory_arch (STB_WEAK)
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

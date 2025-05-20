# Function: <code>early_init_fdt_reserve_self</code>

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
void early_init_fdt_reserve_self();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab6bc)
Location: drivers/of/fdt.c:609
Inline: False
```
**Symbols:**

```
ffff8000114ab6bc-ffff8000114ab728: early_init_fdt_reserve_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void early_init_fdt_reserve_self();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15afe14)
Location: drivers/of/fdt.c:609
Inline: False
Direct callers:
  - arch/arm/mm/init.c:arm_memblock_init
```
**Symbols:**

```
c15afe14-c15afe54: early_init_fdt_reserve_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void early_init_fdt_reserve_self();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bb87c)
Location: drivers/of/fdt.c:609
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
**Symbols:**

```
c0000000013bb87c-c0000000013bb8d0: early_init_fdt_reserve_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void early_init_fdt_reserve_self();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b9aa)
Location: drivers/of/fdt.c:609
Inline: False
```
**Symbols:**

```
ffffffe00003b9aa-ffffffe00003ba0a: early_init_fdt_reserve_self (STB_GLOBAL)
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

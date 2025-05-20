# Function: <code>of_find_next_cache_node</code>

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
struct device_node *of_find_next_cache_node(const struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6c238)
Location: drivers/of/base.c:2194
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_last_cache_level
```
**Symbols:**

```
ffff800010b6c238-ffff800010b6c2dc: of_find_next_cache_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_next_cache_node(const struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4f484)
Location: drivers/of/base.c:2194
Inline: False
Direct callers:
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - drivers/of/base.c:of_find_last_cache_level
```
**Symbols:**

```
c0c4f484-c0c4f544: of_find_next_cache_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_next_cache_node(const struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c46850)
Location: drivers/of/base.c:2194
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/setup_64.c:initialize_cache_info
  - arch/powerpc/kernel/setup_64.c:initialize_cache_info
  - arch/powerpc/kernel/smp.c:cpu_to_l2cache
  - drivers/of/base.c:of_find_last_cache_level
```
**Symbols:**

```
c000000000c46850-c000000000c4691c: of_find_next_cache_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_next_cache_node(const struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00072147a)
Location: drivers/of/base.c:2194
Inline: False
Direct callers:
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
  - drivers/of/base.c:of_find_last_cache_level
```
**Symbols:**

```
ffffffe00072147a-ffffffe0007214ee: of_find_next_cache_node (STB_GLOBAL)
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

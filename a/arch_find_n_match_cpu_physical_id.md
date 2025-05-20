# Function: <code>arch_find_n_match_cpu_physical_id</code>

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
bool arch_find_n_match_cpu_physical_id(struct device_node *cpun, int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6aa48)
Location: drivers/of/base.c:407
Inline: False
Direct callers:
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
ffff800010b6aa48-ffff800010b6abac: arch_find_n_match_cpu_physical_id (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool arch_find_n_match_cpu_physical_id(struct device_node *cpun, int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4dfd0)
Location: drivers/of/base.c:407
Inline: False
Direct callers:
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
c0c4dfd0-c0c4e108: arch_find_n_match_cpu_physical_id (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool arch_find_n_match_cpu_physical_id(struct device_node *cpun, int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44430)
Location: drivers/of/base.c:407
Inline: True
Direct callers:
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
c000000000c44430-c000000000c444cc: arch_find_n_match_cpu_physical_id (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool arch_find_n_match_cpu_physical_id(struct device_node *cpun, int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00072018c)
Location: drivers/of/base.c:407
Inline: False
Direct callers:
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
ffffffe00072018c-ffffffe000720292: arch_find_n_match_cpu_physical_id (STB_WEAK)
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

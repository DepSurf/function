# Function: <code>early_init_dt_alloc_memory_arch</code>

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
void *early_init_dt_alloc_memory_arch(u64 size, u64 align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aa434)
Location: drivers/of/fdt.c:1161
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
ffff8000114aa434-ffff8000114aa494: early_init_dt_alloc_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *early_init_dt_alloc_memory_arch(u64 size, u64 align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15ae950)
Location: drivers/of/fdt.c:1161
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
c15ae950-c15ae9c4: early_init_dt_alloc_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *early_init_dt_alloc_memory_arch(u64 size, u64 align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013ba184)
Location: drivers/of/fdt.c:1161
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
c0000000013ba184-c0000000013ba204: early_init_dt_alloc_memory_arch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *early_init_dt_alloc_memory_arch(u64 size, u64 align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003a7fe)
Location: drivers/of/fdt.c:1161
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
ffffffe00003a7fe-ffffffe00003a854: early_init_dt_alloc_memory_arch (STB_LOCAL)
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

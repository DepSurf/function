# Function: <code>unflatten_device_tree</code>

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
void unflatten_device_tree();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab82c)
Location: drivers/of/fdt.c:1225
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
ffff8000114ab82c-ffff8000114ab87c: unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unflatten_device_tree();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15aff48)
Location: drivers/of/fdt.c:1225
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
c15aff48-c15aff9c: unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unflatten_device_tree();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bba14)
Location: drivers/of/fdt.c:1225
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:setup_arch
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
c0000000013bba14-c0000000013bba7c: unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unflatten_device_tree();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003bb20)
Location: drivers/of/fdt.c:1225
Inline: False
Direct callers:
  - arch/riscv/kernel/setup.c:setup_arch
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
```
**Symbols:**

```
ffffffe00003bb20-ffffffe00003bb6e: unflatten_device_tree (STB_GLOBAL)
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

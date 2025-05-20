# Function: <code>fdt_bus_default_translate</code>

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
int fdt_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffff8000114aba68)
Location: drivers/of/fdt_address.c:87
Inline: False
```
**Symbols:**

```
ffff8000114aba68-ffff8000114abb04: fdt_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c15b01b8)
Location: drivers/of/fdt_address.c:87
Inline: False
```
**Symbols:**

```
c15b01b8-c15b0244: fdt_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c0000000013bbd30)
Location: drivers/of/fdt_address.c:87
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
c0000000013bbd30-c0000000013bbe00: fdt_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffffffe00003bd7a)
Location: drivers/of/fdt_address.c:87
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffffffe00003bd7a-ffffffe00003be2e: fdt_bus_default_translate (STB_LOCAL)
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

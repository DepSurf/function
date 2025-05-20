# Function: <code>of_dma_get_range</code>

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
int of_dma_get_range(struct device_node *np, u64 *dma_addr, u64 *paddr, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b74160)
Location: drivers/of/address.c:921
Inline: False
Direct callers:
  - drivers/of/device.c:of_dma_configure
```
**Symbols:**

```
ffff800010b74160-ffff800010b743a0: of_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_dma_get_range(struct device_node *np, u64 *dma_addr, u64 *paddr, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c561b0)
Location: drivers/of/address.c:921
Inline: False
Direct callers:
  - drivers/of/device.c:of_dma_configure
```
**Symbols:**

```
c0c561b0-c0c56410: of_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_dma_get_range(struct device_node *np, u64 *dma_addr, u64 *paddr, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c50bc0)
Location: drivers/of/address.c:921
Inline: False
Direct callers:
  - drivers/of/device.c:of_dma_configure
```
**Symbols:**

```
c000000000c50bc0-c000000000c50ea8: of_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_dma_get_range(struct device_node *np, u64 *dma_addr, u64 *paddr, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe000727b7e)
Location: drivers/of/address.c:921
Inline: False
Direct callers:
  - drivers/of/device.c:of_dma_configure
```
**Symbols:**

```
ffffffe000727b7e-ffffffe000727da6: of_dma_get_range (STB_GLOBAL)
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

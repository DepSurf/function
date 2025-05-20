# Function: <code>__of_msi_map_rid</code>

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
u32 __of_msi_map_rid(struct device *dev, struct device_node **np, u32 rid_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b74568)
Location: drivers/of/irq.c:579
Inline: False
Direct callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:of_msi_map_rid
```
**Symbols:**

```
ffff800010b74568-ffff800010b7461c: __of_msi_map_rid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 __of_msi_map_rid(struct device *dev, struct device_node **np, u32 rid_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c56988)
Location: drivers/of/irq.c:579
Inline: False
Direct callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:of_msi_map_rid
```
**Symbols:**

```
c0c56988-c0c56a40: __of_msi_map_rid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 __of_msi_map_rid(struct device *dev, struct device_node **np, u32 rid_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c515d0)
Location: drivers/of/irq.c:579
Inline: False
Direct callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:of_msi_map_rid
```
**Symbols:**

```
c000000000c515d0-c000000000c516d4: __of_msi_map_rid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 __of_msi_map_rid(struct device *dev, struct device_node **np, u32 rid_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe000727ef8)
Location: drivers/of/irq.c:579
Inline: False
Direct callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:of_msi_map_rid
```
**Symbols:**

```
ffffffe000727ef8-ffffffe000727f6a: __of_msi_map_rid (STB_LOCAL)
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

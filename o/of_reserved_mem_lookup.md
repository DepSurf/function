# Function: <code>of_reserved_mem_lookup</code>

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
struct reserved_mem *of_reserved_mem_lookup(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffff800010b76750)
Location: drivers/of/of_reserved_mem.c:399
Inline: False
Direct callers:
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe
```
**Symbols:**

```
ffff800010b76750-ffff800010b7680c: of_reserved_mem_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reserved_mem *of_reserved_mem_lookup(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c0c58a90)
Location: drivers/of/of_reserved_mem.c:399
Inline: False
Direct callers:
  - drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe
```
**Symbols:**

```
c0c58a90-c0c58b28: of_reserved_mem_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reserved_mem *of_reserved_mem_lookup(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c000000000c545a0)
Location: drivers/of/of_reserved_mem.c:399
Inline: False
```
**Symbols:**

```
c000000000c545a0-c000000000c54840: of_reserved_mem_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reserved_mem *of_reserved_mem_lookup(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffffffe000729b14)
Location: drivers/of/of_reserved_mem.c:399
Inline: False
```
**Symbols:**

```
ffffffe000729b14-ffffffe000729ba4: of_reserved_mem_lookup (STB_GLOBAL)
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

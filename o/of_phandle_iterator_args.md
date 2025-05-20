# Function: <code>of_phandle_iterator_args</code>

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
int of_phandle_iterator_args(struct of_phandle_iterator *it, uint32_t *args, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b270)
Location: drivers/of/base.c:1391
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
ffff800010b6b270-ffff800010b6b2f0: of_phandle_iterator_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_phandle_iterator_args(struct of_phandle_iterator *it, uint32_t *args, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e644)
Location: drivers/of/base.c:1391
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
c0c4e644-c0c4e6cc: of_phandle_iterator_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_phandle_iterator_args(struct of_phandle_iterator *it, uint32_t *args, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44e30)
Location: drivers/of/base.c:1391
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
c000000000c44e30-c000000000c44ebc: of_phandle_iterator_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_phandle_iterator_args(struct of_phandle_iterator *it, uint32_t *args, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe0007207b6)
Location: drivers/of/base.c:1391
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
ffffffe0007207b6-ffffffe000720846: of_phandle_iterator_args (STB_GLOBAL)
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

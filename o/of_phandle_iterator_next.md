# Function: <code>of_phandle_iterator_next</code>

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
int of_phandle_iterator_next(struct of_phandle_iterator *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6a1b0)
Location: drivers/of/base.c:1311
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:__find_legacy_master_phandle
  - drivers/of/base.c:__of_parse_phandle_with_args
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
ffff800010b6a1b0-ffff800010b6a31c: of_phandle_iterator_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_phandle_iterator_next(struct of_phandle_iterator *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4d10c)
Location: drivers/of/base.c:1311
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
c0c4d10c-c0c4d2ac: of_phandle_iterator_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_phandle_iterator_next(struct of_phandle_iterator *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c42960)
Location: drivers/of/base.c:1311
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
c000000000c42960-c000000000c42b78: of_phandle_iterator_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_phandle_iterator_next(struct of_phandle_iterator *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f35a)
Location: drivers/of/base.c:1311
Inline: False
Direct callers:
  - drivers/of/base.c:__of_parse_phandle_with_args
  - drivers/of/base.c:__of_parse_phandle_with_args
```
**Symbols:**

```
ffffffe00071f35a-ffffffe00071f48c: of_phandle_iterator_next (STB_GLOBAL)
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

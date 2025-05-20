# Function: <code>__of_prop_dup</code>

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
struct property *__of_prop_dup(const struct property *prop, gfp_t allocflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b71250)
Location: drivers/of/dynamic.c:377
Inline: False
Direct callers:
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
ffff800010b71250-ffff800010b71350: __of_prop_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct property *__of_prop_dup(const struct property *prop, gfp_t allocflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c53924)
Location: drivers/of/dynamic.c:377
Inline: False
Direct callers:
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/overlay.c:add_changeset_property
  - drivers/of/overlay.c:add_changeset_property
```
**Symbols:**

```
c0c53924-c0c539e0: __of_prop_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct property *__of_prop_dup(const struct property *prop, gfp_t allocflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4ce80)
Location: drivers/of/dynamic.c:377
Inline: False
Direct callers:
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
c000000000c4ce80-c000000000c4cfb8: __of_prop_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct property *__of_prop_dup(const struct property *prop, gfp_t allocflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000725124)
Location: drivers/of/dynamic.c:377
Inline: False
Direct callers:
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
ffffffe000725124-ffffffe0007251ec: __of_prop_dup (STB_GLOBAL)
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

# Function: <code>__of_add_property</code>

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
int __of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b9d0)
Location: drivers/of/base.c:1816
Inline: False
Direct callers:
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
ffff800010b6b9d0-ffff800010b6ba58: __of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4eda0)
Location: drivers/of/base.c:1816
Inline: False
Direct callers:
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
c0c4eda0-c0c4ee18: __of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c45700)
Location: drivers/of/base.c:1816
Inline: False
Direct callers:
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
c000000000c45700-c000000000c4597c: __of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720e72)
Location: drivers/of/base.c:1816
Inline: False
Direct callers:
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:__of_node_dup
```
**Symbols:**

```
ffffffe000720e72-ffffffe000720ee0: __of_add_property (STB_GLOBAL)
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

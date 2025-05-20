# Function: <code>__of_remove_property</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6bc80)
Location: drivers/of/base.c:1859
Inline: True
Inline callers:
  - drivers/of/base.c:of_remove_property
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffff800010b6bb88-ffff800010b6bc0c: __of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4ef74)
Location: drivers/of/base.c:1859
Inline: True
Inline callers:
  - drivers/of/base.c:of_remove_property
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c0c4eebc-c0c4ef34: __of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c45b98)
Location: drivers/of/base.c:1859
Inline: True
Inline callers:
  - drivers/of/base.c:of_remove_property
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c000000000c45ab0-c000000000c45b28: __of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000721030)
Location: drivers/of/base.c:1859
Inline: True
Inline callers:
  - drivers/of/base.c:of_remove_property
Direct callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffffffe000720f92-ffffffe000720ff4: __of_remove_property (STB_GLOBAL)
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

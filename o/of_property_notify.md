# Function: <code>of_property_notify</code>

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
int of_property_notify(int action, struct device_node *np, struct property *prop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b70a38)
Location: drivers/of/dynamic.c:188
Inline: True
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
ffff800010b70a38-ffff800010b70adc: of_property_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_property_notify(int action, struct device_node *np, struct property *prop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c531e4)
Location: drivers/of/dynamic.c:188
Inline: True
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
c0c531e4-c0c53284: of_property_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int of_property_notify(int action, struct device_node *np, struct property *prop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4c460)
Location: drivers/of/dynamic.c:188
Inline: True
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
c000000000c4c460-c000000000c4c548: of_property_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_property_notify(int action, struct device_node *np, struct property *prop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000724b1a)
Location: drivers/of/dynamic.c:188
Inline: True
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
**Symbols:**

```
ffffffe000724b1a-ffffffe000724b9e: of_property_notify (STB_GLOBAL)
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

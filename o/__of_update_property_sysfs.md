# Function: <code>__of_update_property_sysfs</code>

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
void __of_update_property_sysfs(struct device_node *np, struct property *newprop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b70090)
Location: drivers/of/kobj.c:103
Inline: False
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffff800010b70090-ffff800010b700f4: __of_update_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __of_update_property_sysfs(struct device_node *np, struct property *newprop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c52980)
Location: drivers/of/kobj.c:103
Inline: False
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c0c52980-c0c529e0: __of_update_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __of_update_property_sysfs(struct device_node *np, struct property *newprop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4b390)
Location: drivers/of/kobj.c:103
Inline: False
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c000000000c4b390-c000000000c4b420: __of_update_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __of_update_property_sysfs(struct device_node *np, struct property *newprop, struct property *oldprop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe00072433c)
Location: drivers/of/kobj.c:103
Inline: False
Direct callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffffffe00072433c-ffffffe00072439a: __of_update_property_sysfs (STB_GLOBAL)
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

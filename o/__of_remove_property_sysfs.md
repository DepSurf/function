# Function: <code>__of_remove_property_sysfs</code>

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
void __of_remove_property_sysfs(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b70028)
Location: drivers/of/kobj.c:96
Inline: False
Direct callers:
  - drivers/of/base.c:of_remove_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffff800010b70028-ffff800010b7008c: __of_remove_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __of_remove_property_sysfs(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c5292c)
Location: drivers/of/kobj.c:96
Inline: False
Direct callers:
  - drivers/of/base.c:of_remove_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c0c5292c-c0c52980: __of_remove_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __of_remove_property_sysfs(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4b310)
Location: drivers/of/kobj.c:96
Inline: False
Direct callers:
  - drivers/of/base.c:of_remove_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
c000000000c4b310-c000000000c4b38c: __of_remove_property_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __of_remove_property_sysfs(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe0007242e6)
Location: drivers/of/kobj.c:96
Inline: False
Direct callers:
  - drivers/of/base.c:of_remove_property
  - drivers/of/dynamic.c:__of_changeset_entry_apply
```
**Symbols:**

```
ffffffe0007242e6-ffffffe00072433c: __of_remove_property_sysfs (STB_GLOBAL)
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

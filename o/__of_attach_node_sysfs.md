# Function: <code>__of_attach_node_sysfs</code>

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
int __of_attach_node_sysfs(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b700f8)
Location: drivers/of/kobj.c:115
Inline: False
Direct callers:
  - drivers/of/base.c:of_core_init
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
ffff800010b700f8-ffff800010b70204: __of_attach_node_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __of_attach_node_sysfs(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c529e0)
Location: drivers/of/kobj.c:115
Inline: False
Direct callers:
  - drivers/of/base.c:of_core_init
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
c0c529e0-c0c52adc: __of_attach_node_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __of_attach_node_sysfs(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4b420)
Location: drivers/of/kobj.c:115
Inline: False
Direct callers:
  - drivers/of/base.c:of_core_init
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
c000000000c4b420-c000000000c4b58c: __of_attach_node_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __of_attach_node_sysfs(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe00072439a)
Location: drivers/of/kobj.c:115
Inline: False
Direct callers:
  - drivers/of/base.c:of_core_init
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_attach_node
```
**Symbols:**

```
ffffffe00072439a-ffffffe000724470: __of_attach_node_sysfs (STB_GLOBAL)
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

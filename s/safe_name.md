# Function: <code>safe_name</code>

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
const char *safe_name(struct kobject *kobj, const char *orig_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b6fdf8)
Location: drivers/of/kobj.c:40
Inline: False
Direct callers:
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
ffff800010b6fdf8-ffff800010b6fec4: safe_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *safe_name(struct kobject *kobj, const char *orig_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c52724)
Location: drivers/of/kobj.c:40
Inline: False
Direct callers:
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
c0c52724-c0c527d8: safe_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *safe_name(struct kobject *kobj, const char *orig_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4af90)
Location: drivers/of/kobj.c:40
Inline: False
Direct callers:
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
c000000000c4af90-c000000000c4b0a8: safe_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *safe_name(struct kobject *kobj, const char *orig_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe0007240f2)
Location: drivers/of/kobj.c:40
Inline: False
Direct callers:
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
ffffffe0007240f2-ffffffe0007241b0: safe_name (STB_LOCAL)
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

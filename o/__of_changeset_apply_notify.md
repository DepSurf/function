# Function: <code>__of_changeset_apply_notify</code>

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
int __of_changeset_apply_notify(struct of_changeset *ocs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b71578)
Location: drivers/of/dynamic.c:736
Inline: False
Direct callers:
  - drivers/of/dynamic.c:of_changeset_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffff800010b71578-ffff800010b71640: __of_changeset_apply_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __of_changeset_apply_notify(struct of_changeset *ocs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c53c00)
Location: drivers/of/dynamic.c:736
Inline: True
Direct callers:
  - drivers/of/dynamic.c:of_changeset_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c0c53c00-c0c53cb8: __of_changeset_apply_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __of_changeset_apply_notify(struct of_changeset *ocs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4d2b0)
Location: drivers/of/dynamic.c:736
Inline: True
Direct callers:
  - drivers/of/dynamic.c:of_changeset_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c000000000c4d2b0-c000000000c4d3cc: __of_changeset_apply_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __of_changeset_apply_notify(struct of_changeset *ocs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe0007253b8)
Location: drivers/of/dynamic.c:736
Inline: True
Direct callers:
  - drivers/of/dynamic.c:of_changeset_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffffffe0007253b8-ffffffe00072547a: __of_changeset_apply_notify (STB_GLOBAL)
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

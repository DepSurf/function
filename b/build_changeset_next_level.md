# Function: <code>build_changeset_next_level</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int build_changeset_next_level(struct overlay_changeset *ovcs, struct target *target, const struct device_node *overlay_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/overlay.c (ffff800010b77fb0)
Location: drivers/of/overlay.c:479
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffff800010b77fb0-ffff800010b78094: build_changeset_next_level (STB_LOCAL)
ffff800010b78098-ffff800010b7831c: build_changeset_next_level.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int build_changeset_next_level(struct overlay_changeset *ovcs, struct target *target, const struct device_node *overlay_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c0c5a0e8)
Location: drivers/of/overlay.c:479
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c0c5a0e8-c0c5a3d8: build_changeset_next_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int build_changeset_next_level(struct overlay_changeset *ovcs, struct target *target, const struct device_node *overlay_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c000000000c577d0)
Location: drivers/of/overlay.c:479
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c000000000c577d0-c000000000c57bb4: build_changeset_next_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int build_changeset_next_level(struct overlay_changeset *ovcs, struct target *target, const struct device_node *overlay_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (ffffffe00072ac60)
Location: drivers/of/overlay.c:479
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffffffe00072ac60-ffffffe00072af06: build_changeset_next_level (STB_LOCAL)
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

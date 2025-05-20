# Function: <code>overlay_notify</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/overlay.c (ffff800010b77210)
Location: drivers/of/overlay.c:159
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffff800010b77210-ffff800010b77314: overlay_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int overlay_notify(struct overlay_changeset *ovcs, enum of_overlay_notify_action action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c0c592e4)
Location: drivers/of/overlay.c:159
Inline: False
Direct callers:
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c0c592e4-c0c593dc: overlay_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/overlay.c (c000000000c56000)
Location: drivers/of/overlay.c:159
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c000000000c56000-c000000000c56178: overlay_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/overlay.c (ffffffe00072a4be)
Location: drivers/of/overlay.c:159
Inline: True
Direct callers:
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffffffe00072a4be-ffffffe00072a58e: overlay_notify.isra.0 (STB_LOCAL)
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

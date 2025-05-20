# Function: <code>dup_and_fixup_symbol_prop</code>

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
struct property *dup_and_fixup_symbol_prop(struct overlay_changeset *ovcs, const struct property *prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (ffff800010b776e8)
Location: drivers/of/overlay.c:199
Inline: False
```
**Symbols:**

```
ffff800010b776e8-ffff800010b7791c: dup_and_fixup_symbol_prop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct property *dup_and_fixup_symbol_prop(struct overlay_changeset *ovcs, const struct property *prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c0c59cac)
Location: drivers/of/overlay.c:199
Inline: False
Direct callers:
  - drivers/of/overlay.c:add_changeset_property
```
**Symbols:**

```
c0c59cac-c0c59e9c: dup_and_fixup_symbol_prop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct property *dup_and_fixup_symbol_prop(struct overlay_changeset *ovcs, const struct property *prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c000000000c56b90)
Location: drivers/of/overlay.c:199
Inline: False
```
**Symbols:**

```
c000000000c56b90-c000000000c56e88: dup_and_fixup_symbol_prop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (ffffffe00072aa1c)
Location: drivers/of/overlay.c:199
Inline: True
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

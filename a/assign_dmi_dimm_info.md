# Function: <code>assign_dmi_dimm_info</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:109
Inline: False
```
**Symbols:**

```
ffffffff8198fd20-ffffffff8198ff83: assign_dmi_dimm_info (STB_LOCAL)
ffffffff81c28d3d-ffffffff81c28d60: assign_dmi_dimm_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:109
Inline: False
```
**Symbols:**

```
ffffffff81974300-ffffffff8197451b: assign_dmi_dimm_info (STB_LOCAL)
ffffffff81c1af30-ffffffff81c1af4c: assign_dmi_dimm_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:109
Inline: False
```
**Symbols:**

```
ffffffff81a1d000-ffffffff81a1d21b: assign_dmi_dimm_info (STB_LOCAL)
ffffffff81d2ae60-ffffffff81d2ae7c: assign_dmi_dimm_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:116
Inline: False
```
**Symbols:**

```
ffffffff81b861f0-ffffffff81b86492: assign_dmi_dimm_info (STB_LOCAL)
ffffffff81ef6ff9-ffffffff81ef7015: assign_dmi_dimm_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81d25640)
Location: drivers/edac/ghes_edac.c:115
Inline: False
```
**Symbols:**

```
ffffffff81d25640-ffffffff81d25903: assign_dmi_dimm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81d8e880)
Location: drivers/edac/ghes_edac.c:115
Inline: False
```
**Symbols:**

```
ffffffff81d8e880-ffffffff81d8eb24: assign_dmi_dimm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void assign_dmi_dimm_info(struct dimm_info *dimm, struct memdev_dmi_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81e46190)
Location: drivers/edac/ghes_edac.c:115
Inline: False
```
**Symbols:**

```
ffffffff81e46190-ffffffff81e46434: assign_dmi_dimm_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

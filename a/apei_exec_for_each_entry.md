# Function: <code>apei_exec_for_each_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff814b2c10)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff814b2c10-ffffffff814b2cbc: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81502530)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81502530-ffffffff815025dc: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81526720)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81526720-ffffffff815267cc: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81539630)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81539630-ffffffff815396dc: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8159c190)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff8159c190-ffffffff8159c23e: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff815d3eb0-ffffffff815d3f51: apei_exec_for_each_entry (STB_LOCAL)
ffffffff815d4d56-ffffffff815d4d6e: apei_exec_for_each_entry.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:206
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff815ed660-ffffffff815ed701: apei_exec_for_each_entry (STB_LOCAL)
ffffffff815ee506-ffffffff815ee51e: apei_exec_for_each_entry.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff8161f410-ffffffff8161f4b8: apei_exec_for_each_entry (STB_LOCAL)
ffffffff81620297-ffffffff816202b0: apei_exec_for_each_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81640ef0-ffffffff81640f98: apei_exec_for_each_entry (STB_LOCAL)
ffffffff81641d77-ffffffff81641d90: apei_exec_for_each_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ee775)
Location: drivers/acpi/apei/apei-base.c:198
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8170be25)
Location: drivers/acpi/apei/apei-base.c:198
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ed465)
Location: drivers/acpi/apei/apei-base.c:198
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff817675c5)
Location: drivers/acpi/apei/apei-base.c:198
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8189bc55)
Location: drivers/acpi/apei/apei-base.c:198
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff819e4415)
Location: drivers/acpi/apei/apei-base.c:195
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a2ca35)
Location: drivers/acpi/apei/apei-base.c:195
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a77c75)
Location: drivers/acpi/apei/apei-base.c:195
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffff8000107abbc8)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffff8000107abbc8-ffff8000107abca0: apei_exec_for_each_entry (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff815fd300-ffffffff815fd3a8: apei_exec_for_each_entry (STB_LOCAL)
ffffffff815fe187-ffffffff815fe1a0: apei_exec_for_each_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81634d30-ffffffff81634dd8: apei_exec_for_each_entry (STB_LOCAL)
ffffffff81635bb7-ffffffff81635bd0: apei_exec_for_each_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int apei_exec_for_each_entry(struct apei_exec_context *ctx, apei_exec_entry_func_t func, void *data, int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:198
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_collect_resources
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff8164f040-ffffffff8164f0e8: apei_exec_for_each_entry (STB_LOCAL)
ffffffff8164fec7-ffffffff8164fee0: apei_exec_for_each_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

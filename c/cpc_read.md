# Function: <code>cpc_read</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81525d81)
Location: drivers/acpi/cppc_acpi.c:882
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
```
**Symbols:**

```
ffffffff81525d81-ffffffff81525e49: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81538930)
Location: drivers/acpi/cppc_acpi.c:887
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
```
**Symbols:**

```
ffffffff81538930-ffffffff81538a03: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8159a1b0)
Location: drivers/acpi/cppc_acpi.c:939
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
```
**Symbols:**

```
ffffffff8159a1b0-ffffffff8159a2aa: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d1ab0)
Location: drivers/acpi/cppc_acpi.c:968
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
```
**Symbols:**

```
ffffffff815d1ab0-ffffffff815d1bac: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815eb0d0)
Location: drivers/acpi/cppc_acpi.c:968
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff815eb0d0-ffffffff815eb1cc: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161ce70)
Location: drivers/acpi/cppc_acpi.c:964
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff8161ce70-ffffffff8161cf6e: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163e920)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff8163e920-ffffffff8163ea1e: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816eba40)
Location: drivers/acpi/cppc_acpi.c:948
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff816eba40-ffffffff816ebb26: cpc_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff817090a0)
Location: drivers/acpi/cppc_acpi.c:934
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff817090a0-ffffffff81709182: cpc_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816ea6c0)
Location: drivers/acpi/cppc_acpi.c:926
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff816ea6c0-ffffffff816ea7ac: cpc_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81764450)
Location: drivers/acpi/cppc_acpi.c:926
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
```
**Symbols:**

```
ffffffff81764450-ffffffff817645dc: cpc_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:976
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
```
**Symbols:**

```
ffffffff81898510-ffffffff8189872c: cpc_read.isra.0 (STB_LOCAL)
ffffffff81eba029-ffffffff81eba048: cpc_read.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:979
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
```
**Symbols:**

```
ffffffff819e0850-ffffffff819e0a6c: cpc_read.isra.0 (STB_LOCAL)
ffffffff82092974-ffffffff82092993: cpc_read.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:980
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
```
**Symbols:**

```
ffffffff81a285f0-ffffffff81a28805: cpc_read.isra.0 (STB_LOCAL)
ffffffff821136f6-ffffffff82113715: cpc_read.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:983
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
```
**Symbols:**

```
ffffffff81a737c0-ffffffff81a739d5: cpc_read.isra.0 (STB_LOCAL)
ffffffff821f1069-ffffffff821f1088: cpc_read.isra.0.cold (STB_LOCAL)
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
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a9970)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffff8000107a9970-ffff8000107a9b04: cpc_read (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8160a350)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff8160a350-ffffffff8160a44e: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815fbf90)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff815fbf90-ffffffff815fc08e: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81632760)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff81632760-ffffffff8163285e: cpc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource *reg_res, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164ca90)
Location: drivers/acpi/cppc_acpi.c:966
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
```
**Symbols:**

```
ffffffff8164ca90-ffffffff8164cb8e: cpc_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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

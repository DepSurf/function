# Function: <code>cpc_write</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8152642e)
Location: drivers/acpi/cppc_acpi.c:926
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815392af)
Location: drivers/acpi/cppc_acpi.c:931
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8159abf2)
Location: drivers/acpi/cppc_acpi.c:984
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d27b0)
Location: drivers/acpi/cppc_acpi.c:1013
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815ebf60)
Location: drivers/acpi/cppc_acpi.c:1013
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161dd20)
Location: drivers/acpi/cppc_acpi.c:1009
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163f7d0)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In drivers/acpi/cppc_acpi.c (ffffffff816ec860)
Location: drivers/acpi/cppc_acpi.c:993
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
**Symbols:**

```
ffffffff816ec860-ffffffff816ec925: cpc_write.isra.0 (STB_LOCAL)
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
In drivers/acpi/cppc_acpi.c (ffffffff81709ed0)
Location: drivers/acpi/cppc_acpi.c:979
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
**Symbols:**

```
ffffffff81709ed0-ffffffff81709f95: cpc_write.isra.0 (STB_LOCAL)
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
In drivers/acpi/cppc_acpi.c (ffffffff816eb55e)
Location: drivers/acpi/cppc_acpi.c:971
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
In drivers/acpi/cppc_acpi.c (ffffffff817655c5)
Location: drivers/acpi/cppc_acpi.c:971
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpc_write(int cpu, struct cpc_register_resource *reg_res, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1036
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
```
**Symbols:**

```
ffffffff81899770-ffffffff81899915: cpc_write (STB_LOCAL)
ffffffff81eba048-ffffffff81eba067: cpc_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpc_write(int cpu, struct cpc_register_resource *reg_res, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1039
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
```
**Symbols:**

```
ffffffff819e1b20-ffffffff819e1cc5: cpc_write (STB_LOCAL)
ffffffff82092993-ffffffff820929b2: cpc_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpc_write(int cpu, struct cpc_register_resource *reg_res, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1040
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_auto_sel
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
```
**Symbols:**

```
ffffffff81a29b80-ffffffff81a29d45: cpc_write (STB_LOCAL)
ffffffff8211372a-ffffffff82113749: cpc_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpc_write(int cpu, struct cpc_register_resource *reg_res, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1043
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_auto_sel
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
```
**Symbols:**

```
ffffffff81a74d50-ffffffff81a74f15: cpc_write (STB_LOCAL)
ffffffff821f109d-ffffffff821f10bc: cpc_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107aa92c)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8160b200)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815fce40)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81633610)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164d940)
Location: drivers/acpi/cppc_acpi.c:1011
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

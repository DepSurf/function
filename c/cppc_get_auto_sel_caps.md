# Function: <code>cppc_get_auto_sel_caps</code>

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
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cppc_get_auto_sel_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1441
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
```
**Symbols:**

```
ffffffff82113715-ffffffff8211372a: cppc_get_auto_sel_caps.cold (STB_LOCAL)
ffffffff81a28820-ffffffff81a28a2f: cppc_get_auto_sel_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cppc_get_auto_sel_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:1444
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
```
**Symbols:**

```
ffffffff821f1088-ffffffff821f109d: cppc_get_auto_sel_caps.cold (STB_LOCAL)
ffffffff81a739f0-ffffffff81a73bff: cppc_get_auto_sel_caps (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

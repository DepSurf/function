# Function: <code>uncore_get_alias_name</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncore_get_alias_name(char *pmu_name, struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101e490)
Location: arch/x86/events/intel/uncore.c:845
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - arch/x86/events/intel/uncore_snbep.c:alias_show
```
**Symbols:**

```
ffffffff8101e490-ffffffff8101e4d3: uncore_get_alias_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uncore_get_alias_name(char *pmu_name, struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81020fc0)
Location: arch/x86/events/intel/uncore.c:845
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - arch/x86/events/intel/uncore_snbep.c:alias_show
```
**Symbols:**

```
ffffffff81020fc0-ffffffff8102101f: uncore_get_alias_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uncore_get_alias_name(char *pmu_name, struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81025980)
Location: arch/x86/events/intel/uncore.c:845
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - arch/x86/events/intel/uncore_snbep.c:alias_show
```
**Symbols:**

```
ffffffff81025980-ffffffff810259df: uncore_get_alias_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uncore_get_alias_name(char *pmu_name, struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81025870)
Location: arch/x86/events/intel/uncore.c:866
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - arch/x86/events/intel/uncore_snbep.c:alias_show
```
**Symbols:**

```
ffffffff81025870-ffffffff810258d4: uncore_get_alias_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uncore_get_alias_name(char *pmu_name, struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8102b9d0)
Location: arch/x86/events/intel/uncore.c:866
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - arch/x86/events/intel/uncore_snbep.c:alias_show
```
**Symbols:**

```
ffffffff8102b9d0-ffffffff8102ba34: uncore_get_alias_name (STB_GLOBAL)
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

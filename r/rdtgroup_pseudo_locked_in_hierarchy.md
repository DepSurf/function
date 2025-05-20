# Function: <code>rdtgroup_pseudo_locked_in_hierarchy</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d370)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:831
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105d370-ffffffff8105d45f: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810606f0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff810606f0-ffffffff810607e1: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060fa0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81060fa0-ffffffff81061091: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066c40)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81066c40-ffffffff81066d31: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064e90)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81064e90-ffffffff81064f76: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810654b0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff810654b0-ffffffff81065596: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:824
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81c9cdc9-ffffffff81c9cddd: rdtgroup_pseudo_locked_in_hierarchy.cold (STB_LOCAL)
ffffffff8106f590-ffffffff8106f68c: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:824
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81e4c128-ffffffff81e4c13c: rdtgroup_pseudo_locked_in_hierarchy.cold (STB_LOCAL)
ffffffff8107ce00-ffffffff8107cf0a: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:826
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8205375e-ffffffff82053772: rdtgroup_pseudo_locked_in_hierarchy.cold (STB_LOCAL)
ffffffff8108e180-ffffffff8108e28f: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:826
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff820d1d51-ffffffff820d1d65: rdtgroup_pseudo_locked_in_hierarchy.cold (STB_LOCAL)
ffffffff81091030-ffffffff8109113f: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff821ac9b5-ffffffff821ac9c9: rdtgroup_pseudo_locked_in_hierarchy.cold (STB_LOCAL)
ffffffff810983f0-ffffffff810984ff: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060b20)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81060b20-ffffffff81060c11: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81050f80)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81050f80-ffffffff81051071: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060f50)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81060f50-ffffffff81061041: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rdtgroup_pseudo_locked_in_hierarchy(struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062510)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81062510-ffffffff81062601: rdtgroup_pseudo_locked_in_hierarchy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
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

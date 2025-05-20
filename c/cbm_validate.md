# Function: <code>cbm_validate</code>

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
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044bde)
Location: arch/x86/kernel/cpu/intel_rdt_schemata.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044a31)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048265)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104ab2c)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
```
</details>
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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062760)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81062760-ffffffff8106289e: cbm_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062ec0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81062ec0-ffffffff8106301c: cbm_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8106cd30-ffffffff8106ceab: cbm_validate (STB_LOCAL)
ffffffff81c9ccd6-ffffffff81c9cd08: cbm_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8107a220-ffffffff8107a390: cbm_validate (STB_LOCAL)
ffffffff81e4c02f-ffffffff81e4c05f: cbm_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8108b350-ffffffff8108b493: cbm_validate (STB_LOCAL)
ffffffff82053679-ffffffff82053694: cbm_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8108e2a0-ffffffff8108e3e6: cbm_validate (STB_LOCAL)
ffffffff820d1c6c-ffffffff820d1c87: cbm_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool cbm_validate(char *buf, u32 *data, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81095630-ffffffff81095776: cbm_validate (STB_LOCAL)
ffffffff821ac8d0-ffffffff821ac8eb: cbm_validate.cold (STB_LOCAL)
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

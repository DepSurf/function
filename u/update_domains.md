# Function: <code>update_domains</code>

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
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044cb1)
Location: arch/x86/kernel/cpu/intel_rdt_schemata.c:103
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044d0f)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff810485e5)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104aee8)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b2c0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105b2c0-ffffffff8105b43b: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e630)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105e630-ffffffff8105e7ab: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105eeb0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105eeb0-ffffffff8105f02b: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064a10)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81064a10-ffffffff81064b8a: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062c20)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81062c20-ffffffff81062d75: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810632f0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810632f0-ffffffff81063445: update_domains (STB_GLOBAL)
```
</details>
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
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ea30)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105ea30-ffffffff8105ebab: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104ed60)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8104ed60-ffffffff8104eedb: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ee60)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105ee60-ffffffff8105efdb: update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_domains(struct rdt_resource *r, int closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810603a0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810603a0-ffffffff81060532: update_domains (STB_GLOBAL)
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

# Function: <code>show_doms</code>

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
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044e6c)
Location: arch/x86/kernel/cpu/intel_rdt_schemata.c:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044ecd)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:251
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff810487fd)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104b127)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b8af)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:448
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ec1e)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f49e)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_doms(struct seq_file *s, struct rdt_resource *r, int closid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810643b0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
```
**Symbols:**

```
ffffffff810643b0-ffffffff8106446b: show_doms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_doms(struct seq_file *s, struct rdt_resource *r, int closid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810628a0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
```
**Symbols:**

```
ffffffff810628a0-ffffffff8106295b: show_doms (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810638b3)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:374
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d8b5)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107ae4c)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108c124)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108ef8c)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:459
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8109631c)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:461
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f01e)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104f34e)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f44e)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
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
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810609ae)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>

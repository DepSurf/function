# Function: <code>rdt_bit_usage_show</code>

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
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81056a60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:801
Inline: False
```
**Symbols:**

```
ffffffff81056a60-ffffffff81056d01: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059c40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:795
Inline: False
```
**Symbols:**

```
ffffffff81059c40-ffffffff81059ef4: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a530)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:793
Inline: False
```
**Symbols:**

```
ffffffff8105a530-ffffffff8105a7e4: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060530)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:883
Inline: False
```
**Symbols:**

```
ffffffff81060530-ffffffff810607cf: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e770)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:892
Inline: False
```
**Symbols:**

```
ffffffff8105e770-ffffffff8105ea0f: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:892
Inline: False
```
**Symbols:**

```
ffffffff8105ef90-ffffffff8105f22f: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:898
Inline: False
```
**Symbols:**

```
ffffffff810688f0-ffffffff81068ba0: rdt_bit_usage_show (STB_LOCAL)
ffffffff81c9c832-ffffffff81c9c84b: rdt_bit_usage_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:898
Inline: False
```
**Symbols:**

```
ffffffff81075a20-ffffffff81075cfd: rdt_bit_usage_show (STB_LOCAL)
ffffffff81e4bb5f-ffffffff81e4bb78: rdt_bit_usage_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:900
Inline: False
```
**Symbols:**

```
ffffffff81085a60-ffffffff81085d49: rdt_bit_usage_show (STB_LOCAL)
ffffffff82053179-ffffffff82053192: rdt_bit_usage_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:912
Inline: False
```
**Symbols:**

```
ffffffff81088710-ffffffff810889ee: rdt_bit_usage_show (STB_LOCAL)
ffffffff820d1734-ffffffff820d174d: rdt_bit_usage_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:968
Inline: False
```
**Symbols:**

```
ffffffff8108f7f0-ffffffff8108face: rdt_bit_usage_show (STB_LOCAL)
ffffffff821ac383-ffffffff821ac39c: rdt_bit_usage_show.cold (STB_LOCAL)
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
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a0b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:793
Inline: False
```
**Symbols:**

```
ffffffff8105a0b0-ffffffff8105a364: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104a130)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:793
Inline: False
```
**Symbols:**

```
ffffffff8104a130-ffffffff8104a3e4: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a4e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:793
Inline: False
```
**Symbols:**

```
ffffffff8105a4e0-ffffffff8105a794: rdt_bit_usage_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdt_bit_usage_show(struct kernfs_open_file *of, struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b9a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:793
Inline: False
```
**Symbols:**

```
ffffffff8105b9a0-ffffffff8105bc54: rdt_bit_usage_show (STB_LOCAL)
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

# Function: <code>rdtgroup_mkdir</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810447e0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:913
Inline: True
```
**Symbols:**

```
ffffffff810447e0-ffffffff81044991: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043cf0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1700
Inline: True
```
**Symbols:**

```
ffffffff81043cf0-ffffffff81043f25: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810474a0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1786
Inline: True
```
**Symbols:**

```
ffffffff810474a0-ffffffff810476f4: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049a50)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1887
Inline: True
```
**Symbols:**

```
ffffffff81049a50-ffffffff81049cb9: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059b00)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2785
Inline: True
```
**Symbols:**

```
ffffffff81059b00-ffffffff8105a040: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d080)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2853
Inline: True
```
**Symbols:**

```
ffffffff8105d080-ffffffff8105d2f4: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d990)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2857
Inline: True
```
**Symbols:**

```
ffffffff8105d990-ffffffff8105dbed: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810633f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2950
Inline: False
```
**Symbols:**

```
ffffffff810633f0-ffffffff81063537: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061880)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2982
Inline: False
```
**Symbols:**

```
ffffffff81061880-ffffffff810619c7: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062060)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2978
Inline: False
```
**Symbols:**

```
ffffffff81062060-ffffffff8106219a: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3037
Inline: False
```
**Symbols:**

```
ffffffff8106be40-ffffffff8106bf98: rdtgroup_mkdir (STB_LOCAL)
ffffffff81c9cbaf-ffffffff81c9cbd9: rdtgroup_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3037
Inline: False
```
**Symbols:**

```
ffffffff81079150-ffffffff810792c1: rdtgroup_mkdir (STB_LOCAL)
ffffffff81e4befe-ffffffff81e4bf28: rdtgroup_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3087
Inline: False
```
**Symbols:**

```
ffffffff81089bf0-ffffffff81089d61: rdtgroup_mkdir (STB_LOCAL)
ffffffff8205355a-ffffffff82053584: rdtgroup_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3374
Inline: False
```
**Symbols:**

```
ffffffff8108cc70-ffffffff8108cde1: rdtgroup_mkdir (STB_LOCAL)
ffffffff820d1b6c-ffffffff820d1b96: rdtgroup_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3509
Inline: False
```
**Symbols:**

```
ffffffff81092fb0-ffffffff81093121: rdtgroup_mkdir (STB_LOCAL)
ffffffff821ac79a-ffffffff821ac7c4: rdtgroup_mkdir.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d510)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2857
Inline: True
```
**Symbols:**

```
ffffffff8105d510-ffffffff8105d76d: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d6e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2857
Inline: True
```
**Symbols:**

```
ffffffff8104d6e0-ffffffff8104d93d: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d940)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2857
Inline: True
```
**Symbols:**

```
ffffffff8105d940-ffffffff8105db9d: rdtgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ee60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2857
Inline: True
```
**Symbols:**

```
ffffffff8105ee60-ffffffff8105f0bd: rdtgroup_mkdir (STB_LOCAL)
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

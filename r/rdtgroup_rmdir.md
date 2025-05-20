# Function: <code>rdtgroup_rmdir</code>

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
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044660)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:990
Inline: False
```
**Symbols:**

```
ffffffff81044660-ffffffff810447d4: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810438a0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1809
Inline: False
```
**Symbols:**

```
ffffffff810438a0-ffffffff81043b6e: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046fb0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1895
Inline: False
```
**Symbols:**

```
ffffffff81046fb0-ffffffff81047270: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049560)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1996
Inline: False
```
**Symbols:**

```
ffffffff81049560-ffffffff81049820: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810595b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2901
Inline: False
```
**Symbols:**

```
ffffffff810595b0-ffffffff81059883: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2969
Inline: False
```
**Symbols:**

```
ffffffff8105cb40-ffffffff8105ce0d: rdtgroup_rmdir (STB_LOCAL)
ffffffff8105d4fa-ffffffff8105d50d: rdtgroup_rmdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d420)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973
Inline: False
```
**Symbols:**

```
ffffffff8105d420-ffffffff8105d756: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062ea0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3066
Inline: False
```
**Symbols:**

```
ffffffff81062ea0-ffffffff81063021: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061330)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3085
Inline: False
```
**Symbols:**

```
ffffffff81061330-ffffffff8106149a: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061860)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3081
Inline: False
```
**Symbols:**

```
ffffffff81061860-ffffffff81061b98: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3140
Inline: False
```
**Symbols:**

```
ffffffff8106b540-ffffffff8106b912: rdtgroup_rmdir (STB_LOCAL)
ffffffff81c9cb35-ffffffff81c9cb54: rdtgroup_rmdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3140
Inline: False
```
**Symbols:**

```
ffffffff81078850-ffffffff81078c29: rdtgroup_rmdir (STB_LOCAL)
ffffffff81e4be6a-ffffffff81e4be89: rdtgroup_rmdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089510)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3190
Inline: False
```
**Symbols:**

```
ffffffff81089510-ffffffff8108968b: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c420)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3477
Inline: False
```
**Symbols:**

```
ffffffff8108c420-ffffffff8108c6be: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092700)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3612
Inline: False
```
**Symbols:**

```
ffffffff81092700-ffffffff8109299e: rdtgroup_rmdir (STB_LOCAL)
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
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cfa0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973
Inline: False
```
**Symbols:**

```
ffffffff8105cfa0-ffffffff8105d2d6: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d170)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973
Inline: False
```
**Symbols:**

```
ffffffff8104d170-ffffffff8104d4a6: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d3d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973
Inline: False
```
**Symbols:**

```
ffffffff8105d3d0-ffffffff8105d706: rdtgroup_rmdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdtgroup_rmdir(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e8f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973
Inline: False
```
**Symbols:**

```
ffffffff8105e8f0-ffffffff8105ec26: rdtgroup_rmdir (STB_LOCAL)
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

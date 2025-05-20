# Function: <code>rdtgroup_init</code>

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
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81fce1d6)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1091
Inline: False
```
**Symbols:**

```
ffffffff81fce1d6-ffffffff81fce2e1: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff820aeb59)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1901
Inline: False
```
**Symbols:**

```
ffffffff820aeb59-ffffffff820aec90: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff826b53c6)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1987
Inline: False
```
**Symbols:**

```
ffffffff826b53c6-ffffffff826b5529: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff826df102)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:2088
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
**Symbols:**

```
ffffffff826df102-ffffffff826df265: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828982fc)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3007
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828982fc-ffffffff82898478: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828afec9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3075
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828afec9-ffffffff828b0056: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828b3202)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3079
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b3202-ffffffff828b338f: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff82cd82f5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82cd82f5-ffffffff82cd83a4: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff82fc4257)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82fc4257-ffffffff82fc4306: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff831ce84c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff831ce84c-ffffffff831ce9d9: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff832b0abd)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff832b0abd-ffffffff832b0c4a: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff83461c12)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff83461c12-ffffffff83461da8: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff83e83d90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3401
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff83e83d90-ffffffff83e83f61: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff836a70d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3816
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff836a70d0-ffffffff836a7294: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff838d76b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3954
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff838d76b0-ffffffff838d77dd: rdtgroup_init (STB_GLOBAL)
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
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828a1221)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3079
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828a1221-ffffffff828a13ae: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828993fa)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3079
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828993fa-ffffffff82899587: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828b41e4)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3079
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b41e4-ffffffff828b4371: rdtgroup_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdtgroup_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff828b4212)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3079
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b4212-ffffffff828b439f: rdtgroup_init (STB_GLOBAL)
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

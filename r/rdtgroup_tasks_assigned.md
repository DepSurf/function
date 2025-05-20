# Function: <code>rdtgroup_tasks_assigned</code>

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
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058030)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81058030-ffffffff810580ba: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b5b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105b5b0-ffffffff8105b657: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bec0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105bec0-ffffffff8105bf67: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061d50)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:601
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81061d50-ffffffff81061df7: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060270)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:612
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81060270-ffffffff8106034c: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060460)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:612
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81060460-ffffffff8106053c: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:615
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81c9c8f3-ffffffff81c9c92b: rdtgroup_tasks_assigned.cold (STB_LOCAL)
ffffffff81069610-ffffffff81069723: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:615
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81e4bc2e-ffffffff81e4bc62: rdtgroup_tasks_assigned.cold (STB_LOCAL)
ffffffff810768a0-ffffffff810769c2: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff820532a6-ffffffff820532da: rdtgroup_tasks_assigned.cold (STB_LOCAL)
ffffffff81087380-ffffffff810874a2: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:625
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff820d18c8-ffffffff820d18fc: rdtgroup_tasks_assigned.cold (STB_LOCAL)
ffffffff8108a2e0-ffffffff8108a402: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:630
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff821ac502-ffffffff821ac536: rdtgroup_tasks_assigned.cold (STB_LOCAL)
ffffffff81091400-ffffffff81091522: rdtgroup_tasks_assigned (STB_GLOBAL)
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
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ba40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105ba40-ffffffff8105bae7: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104bc10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8104bc10-ffffffff8104bcb7: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105be70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105be70-ffffffff8105bf17: rdtgroup_tasks_assigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdtgroup_tasks_assigned(struct rdtgroup *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d360)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105d360-ffffffff8105d422: rdtgroup_tasks_assigned (STB_GLOBAL)
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

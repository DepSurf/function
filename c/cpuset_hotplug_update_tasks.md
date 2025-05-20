# Function: <code>cpuset_hotplug_update_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111cfdc)
Location: kernel/cpuset.c:2220
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81124d4c)
Location: kernel/cpuset.c:2241
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112e3a7)
Location: kernel/cpuset.c:2241
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (ffffffff8112fa2a)
Location: kernel/cgroup/cpuset.c:2227
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (ffffffff8113c98e)
Location: kernel/cgroup/cpuset.c:2237
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2238
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2974
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2929
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff81162120-ffffffff81162a55: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff811655ee-ffffffff81165627: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff8116de00-ffffffff8116e731: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff811714de-ffffffff81171517: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81181fb0)
Location: kernel/cgroup/cpuset.c:3019
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff81181fb0-ffffffff811822d3: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117eed0)
Location: kernel/cgroup/cpuset.c:3042
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff8117eed0-ffffffff8117f1f3: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3042
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff8117eed0-ffffffff8117f839: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff81bd6672-ffffffff81bd66ab: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3099
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff811a7090-ffffffff811a7a5c: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff81cb32a2-ffffffff81cb32db: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3139
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff811d8140-ffffffff811d8b1c: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff81e640ba-ffffffff81e640f2: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121d0a0)
Location: kernel/cgroup/cpuset.c:3413
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff8121d0a0-ffffffff8121dd05: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff812334e0)
Location: kernel/cgroup/cpuset.c:3602
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff812334e0-ffffffff81233e10: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8124d310)
Location: kernel/cgroup/cpuset.c:4456
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff8124d310-ffffffff8124da51: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e2620)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffff8000101e2620-ffff8000101e2b50: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c04249c4)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
c04249c4-c0424e60: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000250cf0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
c000000000250cf0-c00000000025148c: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe0001591e6)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffe0001591e6-ffffffe000159766: cpuset_hotplug_update_tasks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff81166420-ffffffff81166d51: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff81169afe-ffffffff81169b37: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff81159660-ffffffff81159f85: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff8115ccfe-ffffffff8115cd37: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff811641f0-ffffffff81164b21: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff811678ce-ffffffff81167907: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset *cs, struct tmpmasks *tmp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:3017
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
**Symbols:**

```
ffffffff811716a0-ffffffff81171fba: cpuset_hotplug_update_tasks (STB_LOCAL)
ffffffff81174f9e-ffffffff81174fd7: cpuset_hotplug_update_tasks.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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

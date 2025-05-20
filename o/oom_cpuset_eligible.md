# Function: <code>oom_cpuset_eligible</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121b2f0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff8121b2f0-ffffffff8121b394: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81228dc0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff81228dc0-ffffffff81228e64: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81255910)
Location: mm/oom_kill.c:86
Inline: True
```
**Symbols:**

```
ffffffff81255910-ffffffff812559b1: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81260590)
Location: mm/oom_kill.c:88
Inline: True
```
**Symbols:**

```
ffffffff81260590-ffffffff81260640: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81264e80)
Location: mm/oom_kill.c:88
Inline: True
```
**Symbols:**

```
ffffffff81264e80-ffffffff81264f30: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff812a16a0)
Location: mm/oom_kill.c:89
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff812a16a0-ffffffff812a1750: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff812f95e0)
Location: mm/oom_kill.c:89
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
```
**Symbols:**

```
ffffffff812f95e0-ffffffff812f969d: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81363550)
Location: mm/oom_kill.c:89
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
```
**Symbols:**

```
ffffffff81363550-ffffffff8136360d: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff813959a0)
Location: mm/oom_kill.c:89
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
```
**Symbols:**

```
ffffffff813959a0-ffffffff81395a7e: oom_cpuset_eligible.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff813bf760)
Location: mm/oom_kill.c:89
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
```
**Symbols:**

```
ffffffff813bf760-ffffffff813bf83e: oom_cpuset_eligible.isra.0 (STB_LOCAL)
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
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b60c0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffff8000102b60c0-ffff8000102b6174: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:120
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036e2e0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
c00000000036e2e0-c00000000036e40c: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:120
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81221410)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff81221410-ffffffff812214b4: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812145c0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff812145c0-ffffffff81214664: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121f1b0)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff8121f1b0-ffffffff8121f254: oom_cpuset_eligible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct *start, struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122e210)
Location: mm/oom_kill.c:85
Inline: False
```
**Symbols:**

```
ffffffff8122e210-ffffffff8122e2c6: oom_cpuset_eligible (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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

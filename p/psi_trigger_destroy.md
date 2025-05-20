# Function: <code>psi_trigger_destroy</code>

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
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6070)
Location: kernel/sched/psi.c:1081
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff810f6070-ffffffff810f61fa: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81101e10)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff81101e10-ffffffff81101f9a: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c830)
Location: kernel/sched/psi.c:1131
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff8110c830-ffffffff8110c9ba: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81109a50)
Location: kernel/sched/psi.c:1145
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff81109a50-ffffffff81109bce: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110b770)
Location: kernel/sched/psi.c:1179
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff8110b770-ffffffff8110b8ee: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void psi_trigger_destroy(struct psi_trigger *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112a5fe)
Location: kernel/sched/psi.c:1155
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_release
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
```
**Symbols:**

```
ffffffff8112a410-ffffffff8112a5d8: psi_trigger_destroy.part.0 (STB_LOCAL)
ffffffff81ca9428-ffffffff81ca9447: psi_trigger_destroy.part.0.cold (STB_LOCAL)
ffffffff8112bf10-ffffffff8112bf26: psi_trigger_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void psi_trigger_destroy(struct psi_trigger *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113ecdd)
Location: kernel/sched/psi.c:1158
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_fop_release
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
```
**Symbols:**

```
ffffffff8113eae0-ffffffff8113ecbf: psi_trigger_destroy.part.0 (STB_LOCAL)
ffffffff81e56ca2-ffffffff81e56cc1: psi_trigger_destroy.part.0.cold (STB_LOCAL)
ffffffff8114cc20-ffffffff8114cc42: psi_trigger_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void psi_trigger_destroy(struct psi_trigger *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1332
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
```
**Symbols:**

```
ffffffff82058264-ffffffff82058283: psi_trigger_destroy.cold (STB_LOCAL)
ffffffff8117b9b0-ffffffff8117bbe3: psi_trigger_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void psi_trigger_destroy(struct psi_trigger *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1380
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
```
**Symbols:**

```
ffffffff820d6b5c-ffffffff820d6b7b: psi_trigger_destroy.cold (STB_LOCAL)
ffffffff8118c5d0-ffffffff8118c88f: psi_trigger_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void psi_trigger_destroy(struct psi_trigger *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1372
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
```
**Symbols:**

```
ffffffff821b1df2-ffffffff821b1e11: psi_trigger_destroy.cold (STB_LOCAL)
ffffffff8119af60-ffffffff8119b238: psi_trigger_destroy (STB_GLOBAL)
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
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff8000101669a0)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffff8000101669a0-ffff800010166b0c: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b3740)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
c03b3740-c03b3928: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001be5c0)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
c0000000001be5c0-c0000000001be7d4: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000108e82)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffe000108e82-ffffffe000108fea: psi_trigger_destroy (STB_LOCAL)
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
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fb120)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff810fb120-ffffffff810fb2aa: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eb340)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff810eb340-ffffffff810eb4ca: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f82e0)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff810f82e0-ffffffff810f846a: psi_trigger_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_trigger_destroy(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103420)
Location: kernel/sched/psi.c:1082
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
**Symbols:**

```
ffffffff81103420-ffffffff811035aa: psi_trigger_destroy (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct psi_trigger *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref *ref</code>
</li>
</ul>
</details>
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

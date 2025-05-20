# Function: <code>psi_trigger_create</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f70d0)
Location: kernel/sched/psi.c:1006
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810f70d0-ffffffff810f7394: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102e60)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81102e60-ffffffff81103124: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ca70)
Location: kernel/sched/psi.c:1056
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8110ca70-ffffffff8110cd0d: psi_trigger_create.part.0 (STB_LOCAL)
ffffffff8110dd20-ffffffff8110dd3f: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff81109c30)
Location: kernel/sched/psi.c:1072
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81109c30-ffffffff81109eb5: psi_trigger_create.part.0 (STB_LOCAL)
ffffffff8110b070-ffffffff8110b08f: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110b930)
Location: kernel/sched/psi.c:1108
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8110b930-ffffffff8110bb80: psi_trigger_create.part.0 (STB_LOCAL)
ffffffff8110cdf0-ffffffff8110ce0f: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112b4d4)
Location: kernel/sched/psi.c:1085
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8112a190-ffffffff8112a40d: psi_trigger_create.part.0 (STB_LOCAL)
ffffffff81ca9409-ffffffff81ca9428: psi_trigger_create.part.0.cold (STB_LOCAL)
ffffffff8112bef0-ffffffff8112bf0c: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1086
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81e5959f-ffffffff81e595b8: psi_trigger_create.cold (STB_LOCAL)
ffffffff8114c740-ffffffff8114ca11: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1255
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_write
  - kernel/cgroup/cgroup.c:pressure_write
```
**Symbols:**

```
ffffffff8205824b-ffffffff82058264: psi_trigger_create.cold (STB_LOCAL)
ffffffff8117b480-ffffffff8117b752: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, enum psi_res res, struct file *file, struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1278
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_write
  - kernel/cgroup/cgroup.c:pressure_write
```
**Symbols:**

```
ffffffff820d6b43-ffffffff820d6b5c: psi_trigger_create.cold (STB_LOCAL)
ffffffff8118bfe0-ffffffff8118c36e: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, enum psi_res res, struct file *file, struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1270
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_write
  - kernel/cgroup/cgroup.c:pressure_write
```
**Symbols:**

```
ffffffff821b1dd9-ffffffff821b1df2: psi_trigger_create.cold (STB_LOCAL)
ffffffff8119a940-ffffffff8119acfd: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167d68)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffff800010167d68-ffff800010167fec: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c03b2fac)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
c03b2fac-c03b3268: psi_trigger_create.part.0 (STB_LOCAL)
c03b4980-c03b49bc: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bfc10)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
c0000000001bfc10-c0000000001bff40: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffe0001095c2)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffe0001095c2-ffffffe0001097f0: psi_trigger_create.part.0 (STB_LOCAL)
ffffffe00010a0d8-ffffffe00010a130: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fc170)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810fc170-ffffffff810fc434: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec380)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810ec380-ffffffff810ec644: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f9330)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810f9330-ffffffff810f95f4: psi_trigger_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct psi_trigger *psi_trigger_create(struct psi_group *group, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81104470)
Location: kernel/sched/psi.c:1007
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81104470-ffffffff81104734: psi_trigger_create (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t nbytes</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, buf, nbytes, res</code> ➡️ <code>group, buf, res</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param added. </b>
<code>struct kernfs_open_file *of</code>
</li>
</ul>
</details>
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

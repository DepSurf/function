# Function: <code>psi_trigger_replace</code>

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
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f73a0)
Location: kernel/sched/psi.c:1148
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810f73a0-ffffffff810f73d3: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103130)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81103130-ffffffff81103163: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110dd40)
Location: kernel/sched/psi.c:1198
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8110dd40-ffffffff8110dd87: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110b090)
Location: kernel/sched/psi.c:1210
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8110b090-ffffffff8110b0d7: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ce10)
Location: kernel/sched/psi.c:1242
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff8110ce10-ffffffff8110ce57: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167ff0)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffff800010167ff0-ffff800010168048: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b49bc)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
c03b49bc-c03b4a18: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bff40)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
c0000000001bff40-c0000000001bffa0: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe00010a130)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffe00010a130-ffffffe00010a18a: psi_trigger_replace (STB_GLOBAL)
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
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fc440)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810fc440-ffffffff810fc473: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec650)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810ec650-ffffffff810ec683: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f9600)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff810f9600-ffffffff810f9633: psi_trigger_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_trigger_replace(void **trigger_ptr, struct psi_trigger *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81104740)
Location: kernel/sched/psi.c:1149
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_release
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
**Symbols:**

```
ffffffff81104740-ffffffff81104773: psi_trigger_replace (STB_GLOBAL)
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

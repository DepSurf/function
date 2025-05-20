# Function: <code>psi_trigger_poll</code>

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
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f7580)
Location: kernel/sched/psi.c:1160
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff810f7580-ffffffff810f761d: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103320)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff81103320-ffffffff811033bd: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d635)
Location: kernel/sched/psi.c:1210
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8110d430-ffffffff8110d557: psi_trigger_poll.part.0 (STB_LOCAL)
ffffffff8110df50-ffffffff8110df6b: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110a925)
Location: kernel/sched/psi.c:1222
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8110a470-ffffffff8110a57c: psi_trigger_poll.part.0 (STB_LOCAL)
ffffffff8110b2a0-ffffffff8110b2bb: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d010)
Location: kernel/sched/psi.c:1254
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8110d010-ffffffff8110d120: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112bf30)
Location: kernel/sched/psi.c:1222
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8112bf30-ffffffff8112bf92: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114cc50)
Location: kernel/sched/psi.c:1225
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8114cc50-ffffffff8114ccca: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117bc50)
Location: kernel/sched/psi.c:1401
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8117bc50-ffffffff8117bccb: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c8f0)
Location: kernel/sched/psi.c:1465
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8118c8f0-ffffffff8118c980: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119b2a0)
Location: kernel/sched/psi.c:1457
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff8119b2a0-ffffffff8119b330: psi_trigger_poll (STB_GLOBAL)
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
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010168400)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffff800010168400-ffff8000101684e0: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c03b3a10)
Location: kernel/sched/psi.c:1161
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
c03b3928-c03b39fc: psi_trigger_poll.part.0 (STB_LOCAL)
c03b4c84-c03b4cbc: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001c01f0)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
c0000000001c01f0-c0000000001c0320: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffe0001098ac)
Location: kernel/sched/psi.c:1161
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffe0001097f0-ffffffe000109892: psi_trigger_poll.part.0 (STB_LOCAL)
ffffffe00010a398-ffffffe00010a3f2: psi_trigger_poll (STB_GLOBAL)
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
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fc630)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff810fc630-ffffffff810fc6cd: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec840)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff810ec840-ffffffff810ec8dd: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f97f0)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff810f97f0-ffffffff810f988d: psi_trigger_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__poll_t psi_trigger_poll(void **trigger_ptr, struct file *file, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81104930)
Location: kernel/sched/psi.c:1161
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/cgroup/cgroup.c:cgroup_pressure_poll
```
**Symbols:**

```
ffffffff81104930-ffffffff811049ec: psi_trigger_poll (STB_GLOBAL)
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

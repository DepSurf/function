# Function: <code>guarantee_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111ae40)
Location: kernel/cpuset.c:336
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_cpus_allowed
```
**Symbols:**

```
ffffffff8111ae40-ffffffff8111ae9a: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123280)
Location: kernel/cpuset.c:335
Inline: True
Direct callers:
  - kernel/cpuset.c:cpuset_cpus_allowed
  - kernel/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81123280-ffffffff81123315: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112bb50)
Location: kernel/cpuset.c:335
Inline: True
Direct callers:
  - kernel/cpuset.c:cpuset_cpus_allowed
  - kernel/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8112bb50-ffffffff8112bbd8: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112d5d0)
Location: kernel/cgroup/cpuset.c:338
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8112d5d0-ffffffff8112d672: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113a4e0)
Location: kernel/cgroup/cpuset.c:349
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8113a4e0-ffffffff8113a582: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:349
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81148c50-ffffffff81148cea: guarantee_online_cpus (STB_LOCAL)
ffffffff8114c247-ffffffff8114c253: guarantee_online_cpus.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81154640)
Location: kernel/cgroup/cpuset.c:406
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81154600-ffffffff8115469a: guarantee_online_cpus (STB_LOCAL)
ffffffff81158e77-ffffffff81158e83: guarantee_online_cpus.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81160b8b)
Location: kernel/cgroup/cpuset.c:368
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81160b50-ffffffff81160be1: guarantee_online_cpus (STB_LOCAL)
ffffffff811655ca-ffffffff811655d6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116c85b)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8116c820-ffffffff8116c8b1: guarantee_online_cpus (STB_LOCAL)
ffffffff811714ba-ffffffff811714c6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:384
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8117e510-ffffffff8117e5a2: guarantee_online_cpus (STB_LOCAL)
ffffffff811831ca-ffffffff811831d6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:384
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8117b380-ffffffff8117b412: guarantee_online_cpus (STB_LOCAL)
ffffffff81be47ff-ffffffff81be480b: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:384
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8117b850-ffffffff8117b8e2: guarantee_online_cpus (STB_LOCAL)
ffffffff81bd6628-ffffffff81bd6634: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct task_struct *tsk, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:400
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff811a3730-ffffffff811a37f4: guarantee_online_cpus (STB_LOCAL)
ffffffff81cb3258-ffffffff81cb3264: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct task_struct *tsk, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:418
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff811d59c0-ffffffff811d5aa5: guarantee_online_cpus (STB_LOCAL)
ffffffff81e640a2-ffffffff81e640ae: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void guarantee_online_cpus(struct task_struct *tsk, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121a3e0)
Location: kernel/cgroup/cpuset.c:501
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8121a3e0-ffffffff8121a516: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void guarantee_online_cpus(struct task_struct *tsk, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81230280)
Location: kernel/cgroup/cpuset.c:501
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach_task
```
**Symbols:**

```
ffffffff81230280-ffffffff812303b6: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void guarantee_online_cpus(struct task_struct *tsk, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81248d10)
Location: kernel/cgroup/cpuset.c:531
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach_task
```
**Symbols:**

```
ffffffff81248d10-ffffffff81248e46: guarantee_online_cpus (STB_LOCAL)
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
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0d08)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffff8000101e0d08-ffff8000101e0d94: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0422378)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
c0422378-c04223c4: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024fdc0)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
c00000000024fdc0-c00000000024fe98: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe0001570a0)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffe0001570a0-ffffffe000157130: guarantee_online_cpus (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164e7b)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81164e40-ffffffff81164ed1: guarantee_online_cpus (STB_LOCAL)
ffffffff81169ada-ffffffff81169ae6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811581ab)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81158170-ffffffff81158201: guarantee_online_cpus (STB_LOCAL)
ffffffff8115ccda-ffffffff8115cce6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162c4b)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81162c10-ffffffff81162ca1: guarantee_online_cpus (STB_LOCAL)
ffffffff811678aa-ffffffff811678b6: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void guarantee_online_cpus(struct cpuset *cs, struct cpumask *pmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811701cb)
Location: kernel/cgroup/cpuset.c:380
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff81170190-ffffffff81170221: guarantee_online_cpus (STB_LOCAL)
ffffffff81174f7a-ffffffff81174f86: guarantee_online_cpus.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpuset *cs</code>
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

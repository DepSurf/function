# Function: <code>generate_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111a7e0)
Location: kernel/cpuset.c:620
Inline: False
Direct callers:
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8111a7e0-ffffffff8111ad01: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81122690)
Location: kernel/cpuset.c:631
Inline: False
Direct callers:
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81122690-ffffffff81122bd3: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112c750)
Location: kernel/cpuset.c:631
Inline: False
Direct callers:
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8112c750-ffffffff8112cc99: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112d9c0)
Location: kernel/cgroup/cpuset.c:634
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8112d9c0-ffffffff8112ded3: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113a590)
Location: kernel/cgroup/cpuset.c:651
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8113a590-ffffffff8113aa6f: generate_sched_domains (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffffffff81149aac)
Location: kernel/cgroup/cpuset.c:651
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
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
In kernel/cgroup/cpuset.c (ffffffff8115579a)
Location: kernel/cgroup/cpuset.c:760
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:721
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81162a60-ffffffff81162ff1: generate_sched_domains (STB_LOCAL)
ffffffff81165627-ffffffff8116564d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8116e740-ffffffff8116ecff: generate_sched_domains (STB_LOCAL)
ffffffff81171517-ffffffff8117153d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:737
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8117f9c0-ffffffff8117ff5f: generate_sched_domains (STB_LOCAL)
ffffffff81183232-ffffffff81183258: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:737
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8117caf0-ffffffff8117d05b: generate_sched_domains (STB_LOCAL)
ffffffff81be4867-ffffffff81be488d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:737
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8117bc70-ffffffff8117c1de: generate_sched_domains (STB_LOCAL)
ffffffff81bd6634-ffffffff81bd665a: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:765
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff811a3800-ffffffff811a3d6e: generate_sched_domains (STB_LOCAL)
ffffffff81cb3264-ffffffff81cb328a: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:805
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff811d5030-ffffffff811d5647: generate_sched_domains (STB_LOCAL)
ffffffff81e6407b-ffffffff81e640a2: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81219620)
Location: kernel/cgroup/cpuset.c:892
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81219620-ffffffff81219ca2: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122f4e0)
Location: kernel/cgroup/cpuset.c:892
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8122f4e0-ffffffff8122fb45: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81247e80)
Location: kernel/cgroup/cpuset.c:956
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81247e80-ffffffff81248514: generate_sched_domains (STB_LOCAL)
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
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0818)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffff8000101e0818-ffff8000101e0d04: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0422414)
Location: kernel/cgroup/cpuset.c:733
Inline: False
```
**Symbols:**

```
c0422414-c04228f8: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000251490)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
c000000000251490-c000000000251b78: generate_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157726)
Location: kernel/cgroup/cpuset.c:733
Inline: False
```
**Symbols:**

```
ffffffe000157726-ffffffe000157b48: generate_sched_domains (STB_LOCAL)
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
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81166d60-ffffffff8116731f: generate_sched_domains (STB_LOCAL)
ffffffff81169b37-ffffffff81169b5d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81159f90-ffffffff8115a54f: generate_sched_domains (STB_LOCAL)
ffffffff8115cd37-ffffffff8115cd5d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81164b30-ffffffff811650ef: generate_sched_domains (STB_LOCAL)
ffffffff81167907-ffffffff8116792d: generate_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int generate_sched_domains(cpumask_var_t **domains, struct sched_domain_attr **attributes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81171fc0-ffffffff81172596: generate_sched_domains (STB_LOCAL)
ffffffff81174fd7-ffffffff81174ffd: generate_sched_domains.cold (STB_LOCAL)
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

# Function: <code>cpu_attach_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a82c0)
Location: kernel/sched/core.c:6026
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810a82c0-ffffffff810a8887: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aae70)
Location: kernel/sched/core.c:5987
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810aae70-ffffffff810ab42a: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1110)
Location: kernel/sched/core.c:6031
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810b1110-ffffffff810b16b0: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cb3f0)
Location: kernel/sched/topology.c:426
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810cb3f0-ffffffff810cba84: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d2ba0)
Location: kernel/sched/topology.c:441
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810d2ba0-ffffffff810d324a: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:433
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810dabf0-ffffffff810daf06: cpu_attach_domain (STB_LOCAL)
ffffffff810dcbdc-ffffffff810dcf0d: cpu_attach_domain.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:632
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810e4740-ffffffff810e4abf: cpu_attach_domain (STB_LOCAL)
ffffffff810e683c-ffffffff810e6b6d: cpu_attach_domain.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810eb700-ffffffff810eba78: cpu_attach_domain (STB_LOCAL)
ffffffff810ed751-ffffffff810ed7b0: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810f70a0-ffffffff810f7428: cpu_attach_domain (STB_LOCAL)
ffffffff810f905b-ffffffff810f9398: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:659
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81101ae0-ffffffff81101ced: cpu_attach_domain (STB_LOCAL)
ffffffff8110340f-ffffffff8110346f: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:687
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81100680-ffffffff811008e0: cpu_attach_domain (STB_LOCAL)
ffffffff81bdcd7e-ffffffff81bdcdde: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:687
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81102820-ffffffff81102a1d: cpu_attach_domain (STB_LOCAL)
ffffffff81bceef9-ffffffff81bcef59: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:687
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8111f3a0-ffffffff8111f610: cpu_attach_domain (STB_LOCAL)
ffffffff81ca759c-ffffffff81ca7647: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:707
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff811493b0-ffffffff81149646: cpu_attach_domain (STB_LOCAL)
ffffffff81e59343-ffffffff81e593ea: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:707
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81177cd0-ffffffff81177fab: cpu_attach_domain (STB_LOCAL)
ffffffff820580db-ffffffff82058134: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:709
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81188960-ffffffff81188c47: cpu_attach_domain (STB_LOCAL)
ffffffff820d69ef-ffffffff820d6a2b: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:725
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81197240-ffffffff81197520: cpu_attach_domain (STB_LOCAL)
ffffffff821b1c85-ffffffff821b1cc1: cpu_attach_domain.cold (STB_LOCAL)
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
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015b3d8)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffff80001015b3d8-ffff80001015b790: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a7e0c)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c03a7e0c-c03a81d8: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001af940)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c0000000001af940-c0000000001afdf4: cpu_attach_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe0001006ea)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffe0001006ea-ffffffe000100a2e: cpu_attach_domain (STB_LOCAL)
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
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810f04a0-ffffffff810f0828: cpu_attach_domain (STB_LOCAL)
ffffffff810f245b-ffffffff810f2798: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810e0510-ffffffff810e0898: cpu_attach_domain (STB_LOCAL)
ffffffff810e24cb-ffffffff810e2808: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810ed5d0-ffffffff810ed958: cpu_attach_domain (STB_LOCAL)
ffffffff810ef58b-ffffffff810ef8c8: cpu_attach_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cpu_attach_domain(struct sched_domain *sd, struct root_domain *rd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:661
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810f8610-ffffffff810f8998: cpu_attach_domain (STB_LOCAL)
ffffffff810fa5db-ffffffff810fa918: cpu_attach_domain.cold (STB_LOCAL)
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

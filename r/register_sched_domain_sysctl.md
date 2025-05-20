# Function: <code>register_sched_domain_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a5e30)
Location: kernel/sched/core.c:5442
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810a5e30-ffffffff810a63d0: register_sched_domain_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cb340)
Location: kernel/sched/debug.c:330
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810cb340-ffffffff810cb8bc: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d1370)
Location: kernel/sched/debug.c:330
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810d1370-ffffffff810d18ef: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d0490)
Location: kernel/sched/debug.c:331
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810d0490-ffffffff810d09e1: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d7e40)
Location: kernel/sched/debug.c:338
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810d7e40-ffffffff810d84a9: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:313
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810e1dd7-ffffffff810e1de3: register_sched_domain_sysctl.cold.12 (STB_LOCAL)
ffffffff810df2a0-ffffffff810df91d: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:314
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810ec527-ffffffff810ec533: register_sched_domain_sysctl.cold.13 (STB_LOCAL)
ffffffff810e9a20-ffffffff810ea09d: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f323f-ffffffff810f3278: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810f0990-ffffffff810f0e81: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810feee5-ffffffff810feef1: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810fc640-ffffffff810fcb3f: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8110961d-ffffffff81109629: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff81107060-ffffffff811072cd: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:351
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81bdda01-ffffffff81bdda0d: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff81105870-ffffffff81105add: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161a40)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffff800010161a40-ffff800010161f18: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ae204)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
c03ae204-c03ae72c: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b7b90)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
c0000000001b7b90-c0000000001b8214: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000105854)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffe000105854-ffffffe000105c8e: register_sched_domain_sysctl (STB_GLOBAL)
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
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f8205-ffffffff810f8211: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810f5970-ffffffff810f5e6f: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810e83d5-ffffffff810e83e1: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810e5b30-ffffffff810e602f: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f5415-ffffffff810f5421: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810f2b70-ffffffff810f306f: register_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void register_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:297
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81100415-ffffffff81100421: register_sched_domain_sysctl.cold (STB_LOCAL)
ffffffff810fdb70-ffffffff810fe06f: register_sched_domain_sysctl (STB_GLOBAL)
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

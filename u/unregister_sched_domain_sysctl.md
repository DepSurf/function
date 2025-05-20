# Function: <code>unregister_sched_domain_sysctl</code>

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
In kernel/sched/core.c (ffffffff810afcdb)
Location: kernel/sched/core.c:5467
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cb8c0)
Location: kernel/sched/debug.c:355
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810cb8c0-ffffffff810cb8f8: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d18f0)
Location: kernel/sched/debug.c:355
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810d18f0-ffffffff810d1928: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d09f0)
Location: kernel/sched/debug.c:356
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810d09f0-ffffffff810d0a28: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d84d0)
Location: kernel/sched/debug.c:403
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810d84d0-ffffffff810d84f2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810df940)
Location: kernel/sched/debug.c:378
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810df940-ffffffff810df962: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810ea0c0)
Location: kernel/sched/debug.c:379
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810ea0c0-ffffffff810ea0e2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f0eb0)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810f0eb0-ffffffff810f0ed2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fcb60)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810fcb60-ffffffff810fcb82: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff811072f0)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff811072f0-ffffffff81107312: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81105b00)
Location: kernel/sched/debug.c:420
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff81105b00-ffffffff81105b22: unregister_sched_domain_sysctl (STB_GLOBAL)
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
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161f80)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffff800010161f80-ffff800010161fb4: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ae77c)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
c03ae77c-c03ae7ac: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b8270)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
c0000000001b8270-c0000000001b82bc: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000105cda)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffe000105cda-ffffffe000105d0e: unregister_sched_domain_sysctl (STB_GLOBAL)
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
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f5e90)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810f5e90-ffffffff810f5eb2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810e6050)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810e6050-ffffffff810e6072: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f3090)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810f3090-ffffffff810f30b2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fe090)
Location: kernel/sched/debug.c:366
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810fe090-ffffffff810fe0b2: unregister_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

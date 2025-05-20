# Function: <code>update_sched_domain_debugfs</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:387
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_init_debug
```
**Symbols:**

```
ffffffff81bcfb66-ffffffff81bcfb72: update_sched_domain_debugfs.cold (STB_LOCAL)
ffffffff811077b0-ffffffff81107a29: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:393
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_init_debug
```
**Symbols:**

```
ffffffff81ca8395-ffffffff81ca83a1: update_sched_domain_debugfs.cold (STB_LOCAL)
ffffffff81125870-ffffffff81125b1c: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:393
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
```
**Symbols:**

```
ffffffff81e5827a-ffffffff81e58286: update_sched_domain_debugfs.cold (STB_LOCAL)
ffffffff81145f70-ffffffff8114624d: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81173150)
Location: kernel/sched/debug.c:394
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
```
**Symbols:**

```
ffffffff81173150-ffffffff8117347f: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a85a)
Location: kernel/sched/debug.c:432
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_verbose_write
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_verbose_write
```
**Symbols:**

```
ffffffff811826a0-ffffffff81182a7c: update_sched_domain_debugfs.part.0 (STB_LOCAL)
ffffffff820d6908-ffffffff820d691c: update_sched_domain_debugfs.cold (STB_LOCAL)
ffffffff81184040-ffffffff81184085: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_sched_domain_debugfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199170)
Location: kernel/sched/debug.c:430
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_verbose_write
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_verbose_write
```
**Symbols:**

```
ffffffff81190f00-ffffffff811912ff: update_sched_domain_debugfs.part.0 (STB_LOCAL)
ffffffff821b1b94-ffffffff821b1ba8: update_sched_domain_debugfs.cold (STB_LOCAL)
ffffffff811926f0-ffffffff81192735: update_sched_domain_debugfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

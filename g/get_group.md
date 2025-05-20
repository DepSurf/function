# Function: <code>get_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int get_group(int cpu, struct sd_data *sdd, struct sched_group **sg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a5b80)
Location: kernel/sched/core.c:6206
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810a5b80-ffffffff810a5c03: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int get_group(int cpu, struct sd_data *sdd, struct sched_group **sg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b21bc)
Location: kernel/sched/core.c:6172
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810a9f30-ffffffff810a9fb3: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int get_group(int cpu, struct sd_data *sdd, struct sched_group **sg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b85e7)
Location: kernel/sched/core.c:6217
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810afe80-ffffffff810aff05: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cce58)
Location: kernel/sched/topology.c:834
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d3dab)
Location: kernel/sched/topology.c:836
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810dbb35)
Location: kernel/sched/topology.c:828
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810e5748)
Location: kernel/sched/topology.c:1028
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ec311)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f7dbc)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101490)
Location: kernel/sched/topology.c:1055
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_groups
```
**Symbols:**

```
ffffffff81101490-ffffffff811015c8: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ffff0)
Location: kernel/sched/topology.c:1116
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_groups
```
**Symbols:**

```
ffffffff810ffff0-ffffffff81100128: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811020c0)
Location: kernel/sched/topology.c:1147
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff811020c0-ffffffff811021fb: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111e610)
Location: kernel/sched/topology.c:1161
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8111e610-ffffffff8111e7cf: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81144b40)
Location: kernel/sched/topology.c:1177
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81144b40-ffffffff81144d00: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81171ff0)
Location: kernel/sched/topology.c:1177
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_groups
```
**Symbols:**

```
ffffffff81171ff0-ffffffff811721b0: get_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1184
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_groups
```
**Symbols:**

```
ffffffff811821f0-ffffffff811824cc: get_group (STB_LOCAL)
ffffffff820d6745-ffffffff820d677f: get_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sched_group *get_group(int cpu, struct sd_data *sdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1199
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_groups
```
**Symbols:**

```
ffffffff81190a50-ffffffff81190d2c: get_group (STB_LOCAL)
ffffffff821b1977-ffffffff821b19b1: get_group.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015c20c)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a8bf0)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b09a0)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101460)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f11bc)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e122c)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ee2ec)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f932c)
Location: kernel/sched/topology.c:1057
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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

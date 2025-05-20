# Function: <code>cpufreq_set_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b0760)
Location: drivers/cpufreq/cpufreq.c:2089
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff816b0760-ffffffff816b0ab1: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817131d0)
Location: drivers/cpufreq/cpufreq.c:2192
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff817131d0-ffffffff817134d3: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81745020)
Location: drivers/cpufreq/cpufreq.c:2164
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff81745020-ffffffff817452e7: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763730)
Location: drivers/cpufreq/cpufreq.c:2167
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff81763730-ffffffff81763a17: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9710)
Location: drivers/cpufreq/cpufreq.c:2200
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff817d9710-ffffffff817d9a0c: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81822280)
Location: drivers/cpufreq/cpufreq.c:2198
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff81822280-ffffffff81822500: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184e100)
Location: drivers/cpufreq/cpufreq.c:2199
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffffffff8184e100-ffffffff8184e3d6: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_policy *new_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818912b0)
Location: drivers/cpufreq/cpufreq.c:2362
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818912b0-ffffffff8189162c: cpufreq_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c34a0)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818c34a0-ffffffff818c37fc: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995880)
Location: drivers/cpufreq/cpufreq.c:2411
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81995880-ffffffff81995bfa: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998750)
Location: drivers/cpufreq/cpufreq.c:2488
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81998750-ffffffff81998ab7: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d270)
Location: drivers/cpufreq/cpufreq.c:2494
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff8197d270-ffffffff8197d585: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2496
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81a262e0-ffffffff81a26616: cpufreq_set_policy (STB_LOCAL)
ffffffff81d2c098-ffffffff81d2c0ac: cpufreq_set_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2536
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81b8fcd0-ffffffff81b902cc: cpufreq_set_policy (STB_LOCAL)
ffffffff81ef8306-ffffffff81ef8351: cpufreq_set_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2533
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81d2fe40-ffffffff81d30425: cpufreq_set_policy (STB_LOCAL)
ffffffff820a8ddd-ffffffff820a8e4d: cpufreq_set_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2540
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81d99120-ffffffff81d99705: cpufreq_set_policy (STB_LOCAL)
ffffffff82129ff6-ffffffff8212a066: cpufreq_set_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2581
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81e50da0-ffffffff81e51377: cpufreq_set_policy (STB_LOCAL)
ffffffff8220bdd0-ffffffff8220be40: cpufreq_set_policy.cold (STB_LOCAL)
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
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b20e38)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffff800010b20e38-ffff800010b211c8: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfb490)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
c0bfb490-c0bfb858: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14aa0)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
c000000000c14aa0-c000000000c14f1c: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867bc0)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81867bc0-ffffffff81867f1c: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81830870)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81830870-ffffffff81830bcc: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8950)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818b8950-ffffffff818b8cac: cpufreq_set_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy *policy, struct cpufreq_governor *new_gov, unsigned int new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4c10)
Location: drivers/cpufreq/cpufreq.c:2374
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818d4c10-ffffffff818d4f88: cpufreq_set_policy (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_governor *new_gov</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int new_pol</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpufreq_policy *new_policy</code>
</li>
</ul>
</details>
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

# Function: <code>static_key_enable_cpuslocked</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8190)
Location: kernel/jump_label.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff811c8190-ffffffff811c820b: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8590)
Location: kernel/jump_label.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff811e8590-ffffffff811e860b: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9250)
Location: kernel/jump_label.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff811f9250-ffffffff811f92d0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812111d0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff812111d0-ffffffff81211250: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ee80)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff8121ee80-ffffffff8121ef00: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124acc0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff8124acc0-ffffffff8124ad46: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812550b0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff812550b0-ffffffff81255136: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812595b0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff812595b0-ffffffff81259636: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff81cb9bc6-ffffffff81cb9bdb: static_key_enable_cpuslocked.cold (STB_LOCAL)
ffffffff81295260-ffffffff812952f5: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff81e6b1c0-ffffffff81e6b1d5: static_key_enable_cpuslocked.cold (STB_LOCAL)
ffffffff812eb010-ffffffff812eb0c0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff82061f3e-ffffffff82061f53: static_key_enable_cpuslocked.cold (STB_LOCAL)
ffffffff81355050-ffffffff81355100: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff820e176c-ffffffff820e1781: static_key_enable_cpuslocked.cold (STB_LOCAL)
ffffffff81386540-ffffffff813865f0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff821be1cf-ffffffff821be1e4: static_key_enable_cpuslocked.cold (STB_LOCAL)
ffffffff813afa00-ffffffff813afab0: static_key_enable_cpuslocked (STB_GLOBAL)
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
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab010)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffff8000102ab010-ffff8000102ab0d0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ebd0)
Location: kernel/jump_label.c:164
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
c00000000035ebd0-c00000000035ece8: static_key_enable_cpuslocked (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812174d0)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff812174d0-ffffffff81217550: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a230)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff8120a230-ffffffff8120a2b0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215270)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff81215270-ffffffff812152f0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void static_key_enable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81224260)
Location: kernel/jump_label.c:164
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_enable
```
**Symbols:**

```
ffffffff81224260-ffffffff812242e0: static_key_enable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

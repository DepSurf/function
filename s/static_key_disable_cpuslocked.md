# Function: <code>static_key_disable_cpuslocked</code>

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
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8240)
Location: kernel/jump_label.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff811c8240-ffffffff811c82be: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8640)
Location: kernel/jump_label.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff811e8640-ffffffff811e86c1: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9300)
Location: kernel/jump_label.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff811f9300-ffffffff811f9386: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211280)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff81211280-ffffffff81211306: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ef30)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff8121ef30-ffffffff8121efb6: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ad80)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff8124ad80-ffffffff8124ae06: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255170)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff81255170-ffffffff812551f6: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259670)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff81259670-ffffffff812596f6: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff81cb9bdb-ffffffff81cb9bef: static_key_disable_cpuslocked.cold (STB_LOCAL)
ffffffff81295330-ffffffff812953c2: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff81e6b1d5-ffffffff81e6b1ea: static_key_disable_cpuslocked.cold (STB_LOCAL)
ffffffff812eb0f0-ffffffff812eb19a: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff82061f53-ffffffff82061f68: static_key_disable_cpuslocked.cold (STB_LOCAL)
ffffffff81355150-ffffffff813551fa: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff820e1781-ffffffff820e1796: static_key_disable_cpuslocked.cold (STB_LOCAL)
ffffffff81386640-ffffffff813866ea: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
  - mm/vmscan.c:lru_gen_change_state
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff821be1e4-ffffffff821be1f9: static_key_disable_cpuslocked.cold (STB_LOCAL)
ffffffff813afb00-ffffffff813afbaa: static_key_disable_cpuslocked (STB_GLOBAL)
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
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab238)
Location: kernel/jump_label.c:195
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffff8000102ab238-ffff8000102ab30c: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ee10)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
c00000000035ee10-c00000000035ef38: static_key_disable_cpuslocked (STB_GLOBAL)
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
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217580)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff81217580-ffffffff81217606: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a2e0)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff8120a2e0-ffffffff8120a366: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215320)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff81215320-ffffffff812153a6: static_key_disable_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void static_key_disable_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81224310)
Location: kernel/jump_label.c:195
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/sched/debug.c:sched_feat_write
  - kernel/jump_label.c:static_key_disable
```
**Symbols:**

```
ffffffff81224310-ffffffff81224396: static_key_disable_cpuslocked (STB_GLOBAL)
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

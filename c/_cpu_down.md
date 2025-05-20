# Function: <code>_cpu_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081500)
Location: kernel/cpu.c:339
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_down
  - kernel/cpu.c:disable_nonboot_cpus
```
**Symbols:**

```
ffffffff81081500-ffffffff810817f7: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81892910)
Location: kernel/cpu.c:796
Inline: False
Direct callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81892910-ffffffff81892a51: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff818c7260)
Location: kernel/cpu.c:762
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff818c7260-ffffffff818c7352: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff818fe9b0)
Location: kernel/cpu.c:685
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff818fe9b0-ffffffff818feaa9: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81988ae0)
Location: kernel/cpu.c:854
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81988ae0-ffffffff81988ce4: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff819e5430)
Location: kernel/cpu.c:940
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff819e5430-ffffffff819e5622: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81a20660)
Location: kernel/cpu.c:955
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81a20660-ffffffff81a2083e: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81a90b80)
Location: kernel/cpu.c:967
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81a90b80-ffffffff81a90d6d: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81ac7ec0)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81ac7ec0-ffffffff81ac80ae: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81bc09c0)
Location: kernel/cpu.c:992
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81bc09c0-ffffffff81bc0bd2: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81c39a50)
Location: kernel/cpu.c:996
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81c39a50-ffffffff81c39c62: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81c2bee0)
Location: kernel/cpu.c:1096
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81c2bee0-ffffffff81c2c236: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81d4a660)
Location: kernel/cpu.c:1120
Inline: False
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81d4a660-ffffffff81d4a927: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81f19ce0)
Location: kernel/cpu.c:1126
Inline: False
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81f19ce0-ffffffff81f19fc6: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff820c1950)
Location: kernel/cpu.c:1152
Inline: False
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff820c1950-ffffffff820c1be8: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82145620)
Location: kernel/cpu.c:1404
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:__cpu_down_maps_locked
```
**Symbols:**

```
ffffffff82145620-ffffffff821458b3: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82227d40)
Location: kernel/cpu.c:1439
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:__cpu_down_maps_locked
```
**Symbols:**

```
ffffffff82227d40-ffffffff82227fd3: _cpu_down (STB_LOCAL)
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff800010d9bce8)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffff800010d9bce8-ffff800010d9bf08: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0e98380)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
c0e98380-c0e985a8: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000141450)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
c000000000141450-c000000000141750: _cpu_down (STB_LOCAL)
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81a66d30)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81a66d30-ffffffff81a66f1e: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81a237f0)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81a237f0-ffffffff81a239de: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81ad3140)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81ad3140-ffffffff81ad332e: _cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81adf640)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
```
**Symbols:**

```
ffffffff81adf640-ffffffff81adf82e: _cpu_down (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state target</code>
</li>
</ul>
</details>
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

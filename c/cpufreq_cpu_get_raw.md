# Function: <code>cpufreq_cpu_get_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816ae760)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
Direct callers:
  - drivers/cpufreq/cpufreq_conservative.c:dbs_cpufreq_notifier
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff816ae760-ffffffff816ae79a: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817121e8)
Location: drivers/cpufreq/cpufreq.c:195
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff817100c0-ffffffff817100f2: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81744a58)
Location: drivers/cpufreq/cpufreq.c:195
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff817420a0-ffffffff817420d5: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817630ea)
Location: drivers/cpufreq/cpufreq.c:195
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81760710-ffffffff81760745: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d909a)
Location: drivers/cpufreq/cpufreq.c:201
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff817d66e0-ffffffff817d6715: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81821caa)
Location: drivers/cpufreq/cpufreq.c:185
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8181f3d0-ffffffff8181f405: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184db2a)
Location: drivers/cpufreq/cpufreq.c:185
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8184b270-ffffffff8184b2a5: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188e4b0)
Location: drivers/cpufreq/cpufreq.c:177
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8188e4b0-ffffffff8188e4e2: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0640)
Location: drivers/cpufreq/cpufreq.c:180
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818c0640-ffffffff818c0672: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994240)
Location: drivers/cpufreq/cpufreq.c:185
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81994240-ffffffff81994272: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996f00)
Location: drivers/cpufreq/cpufreq.c:185
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81996f00-ffffffff81996f32: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197bbb0)
Location: drivers/cpufreq/cpufreq.c:182
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8197bbb0-ffffffff8197bbe2: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a24e00)
Location: drivers/cpufreq/cpufreq.c:182
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81a24e00-ffffffff81a24e55: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c900)
Location: drivers/cpufreq/cpufreq.c:183
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81b8c900-ffffffff81b8c969: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c350)
Location: drivers/cpufreq/cpufreq.c:183
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81d2c350-ffffffff81d2c3b9: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d955e0)
Location: drivers/cpufreq/cpufreq.c:188
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81d955e0-ffffffff81d95649: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d0d0)
Location: drivers/cpufreq/cpufreq.c:189
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81e4d0d0-ffffffff81e4d139: cpufreq_cpu_get_raw (STB_GLOBAL)
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
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1f62c)
Location: drivers/cpufreq/cpufreq.c:180
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
**Symbols:**

```
ffff800010b1ce58-ffff800010b1cebc: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9dc0)
Location: drivers/cpufreq/cpufreq.c:180
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
**Symbols:**

```
c0bf7d20-c0bf7d80: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c1278c)
Location: drivers/cpufreq/cpufreq.c:180
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
**Symbols:**

```
c000000000c0f8b0-c000000000c0f914: cpufreq_cpu_get_raw (STB_GLOBAL)
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
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864d60)
Location: drivers/cpufreq/cpufreq.c:180
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81864d60-ffffffff81864d92: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182da10)
Location: drivers/cpufreq/cpufreq.c:180
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8182da10-ffffffff8182da42: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5af0)
Location: drivers/cpufreq/cpufreq.c:180
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818b5af0-ffffffff818b5b22: cpufreq_cpu_get_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get_raw(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1da0)
Location: drivers/cpufreq/cpufreq.c:180
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818d1da0-ffffffff818d1dd2: cpufreq_cpu_get_raw (STB_GLOBAL)
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

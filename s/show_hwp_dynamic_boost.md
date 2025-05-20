# Function: <code>show_hwp_dynamic_boost</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182a7f0)
Location: drivers/cpufreq/intel_pstate.c:1050
Inline: False
```
**Symbols:**

```
ffffffff8182a7f0-ffffffff8182a816: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81856950)
Location: drivers/cpufreq/intel_pstate.c:1112
Inline: False
```
**Symbols:**

```
ffffffff81856950-ffffffff81856976: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a000)
Location: drivers/cpufreq/intel_pstate.c:1149
Inline: False
```
**Symbols:**

```
ffffffff8189a000-ffffffff8189a026: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc000)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
```
**Symbols:**

```
ffffffff818cc000-ffffffff818cc026: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e290)
Location: drivers/cpufreq/intel_pstate.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8199e290-ffffffff8199e2b6: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1000)
Location: drivers/cpufreq/intel_pstate.c:1302
Inline: False
```
**Symbols:**

```
ffffffff819a1000-ffffffff819a1026: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985b30)
Location: drivers/cpufreq/intel_pstate.c:1302
Inline: False
```
**Symbols:**

```
ffffffff81985b30-ffffffff81985b56: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1402
Inline: False
```
**Symbols:**

```
ffffffff81a2f970-ffffffff81a2f9af: show_hwp_dynamic_boost (STB_LOCAL)
ffffffff81d2c964-ffffffff81d2c97f: show_hwp_dynamic_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1436
Inline: False
```
**Symbols:**

```
ffffffff81b9b6c0-ffffffff81b9b708: show_hwp_dynamic_boost (STB_LOCAL)
ffffffff81ef8c90-ffffffff81ef8cab: show_hwp_dynamic_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81d3d000-ffffffff81d3d048: show_hwp_dynamic_boost (STB_LOCAL)
ffffffff820a9072-ffffffff820a908d: show_hwp_dynamic_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1431
Inline: False
```
**Symbols:**

```
ffffffff81da7bd0-ffffffff81da7c18: show_hwp_dynamic_boost (STB_LOCAL)
ffffffff8212a48f-ffffffff8212a4aa: show_hwp_dynamic_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1455
Inline: False
```
**Symbols:**

```
ffffffff81e5f900-ffffffff81e5f948: show_hwp_dynamic_boost (STB_LOCAL)
ffffffff8220c254-ffffffff8220c26f: show_hwp_dynamic_boost.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186fc00)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
```
**Symbols:**

```
ffffffff8186fc00-ffffffff8186fc26: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839180)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
```
**Symbols:**

```
ffffffff81839180-ffffffff818391a6: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c14b0)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
```
**Symbols:**

```
ffffffff818c14b0-ffffffff818c14d6: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t show_hwp_dynamic_boost(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd7c0)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
```
**Symbols:**

```
ffffffff818dd7c0-ffffffff818dd7e6: show_hwp_dynamic_boost (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
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

# Function: <code>store_energy_efficiency</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a23b0)
Location: drivers/cpufreq/intel_pstate.c:1338
Inline: False
```
**Symbols:**

```
ffffffff819a23b0-ffffffff819a240a: store_energy_efficiency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81987650)
Location: drivers/cpufreq/intel_pstate.c:1338
Inline: False
```
**Symbols:**

```
ffffffff81987650-ffffffff819876aa: store_energy_efficiency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1438
Inline: False
```
**Symbols:**

```
ffffffff81a31360-ffffffff81a313d0: store_energy_efficiency (STB_LOCAL)
ffffffff81d2ca52-ffffffff81d2ca67: store_energy_efficiency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81b9d580-ffffffff81b9d600: store_energy_efficiency (STB_LOCAL)
ffffffff81ef8d9c-ffffffff81ef8db1: store_energy_efficiency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1447
Inline: False
```
**Symbols:**

```
ffffffff81d3efd0-ffffffff81d3f050: store_energy_efficiency (STB_LOCAL)
ffffffff820a9149-ffffffff820a915e: store_energy_efficiency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1467
Inline: False
```
**Symbols:**

```
ffffffff81da9b50-ffffffff81da9bd0: store_energy_efficiency (STB_LOCAL)
ffffffff8212a552-ffffffff8212a567: store_energy_efficiency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t store_energy_efficiency(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1491
Inline: False
```
**Symbols:**

```
ffffffff81e620e0-ffffffff81e62160: store_energy_efficiency (STB_LOCAL)
ffffffff8220c347-ffffffff8220c35c: store_energy_efficiency.cold (STB_LOCAL)
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

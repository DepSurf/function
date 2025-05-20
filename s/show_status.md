# Function: <code>show_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff814b2a63)
Location: drivers/acpi/bgrt.c:26
Inline: False
```
**Symbols:**

```
ffffffff814b2a63-ffffffff814b2a8f: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff81502384)
Location: drivers/acpi/bgrt.c:27
Inline: False
```
**Symbols:**

```
ffffffff81502384-ffffffff815023b0: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff815250d1)
Location: drivers/acpi/bgrt.c:27
Inline: False
```
**Symbols:**

```
ffffffff815250d1-ffffffff815250fd: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff815379b0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176be50)
Location: drivers/cpufreq/intel_pstate.c:1001
Inline: False
```
**Symbols:**

```
ffffffff815379b0-ffffffff815379d8: show_status (STB_LOCAL)
ffffffff8176be50-ffffffff8176bec2: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff81599120)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e1cc0)
Location: drivers/cpufreq/intel_pstate.c:816
Inline: False
```
**Symbols:**

```
ffffffff81599120-ffffffff81599148: show_status (STB_LOCAL)
ffffffff817e1cc0-ffffffff817e1d32: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff815d0980)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182a9b0)
Location: drivers/cpufreq/intel_pstate.c:847
Inline: False
```
**Symbols:**

```
ffffffff815d0980-ffffffff815d09a8: show_status (STB_LOCAL)
ffffffff8182a9b0-ffffffff8182aa22: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff815e9fb0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81856b10)
Location: drivers/cpufreq/intel_pstate.c:909
Inline: False
```
**Symbols:**

```
ffffffff815e9fb0-ffffffff815e9fd8: show_status (STB_LOCAL)
ffffffff81856b10-ffffffff81856b82: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff8161bd10)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a1c0)
Location: drivers/cpufreq/intel_pstate.c:946
Inline: False
```
**Symbols:**

```
ffffffff8161bd10-ffffffff8161bd38: show_status (STB_LOCAL)
ffffffff8189a1c0-ffffffff8189a239: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff8163d7b0)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc1c0)
Location: drivers/cpufreq/intel_pstate.c:945
Inline: False
```
**Symbols:**

```
ffffffff8163d7b0-ffffffff8163d7d8: show_status (STB_LOCAL)
ffffffff818cc1c0-ffffffff818cc239: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff816ea970)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e450)
Location: drivers/cpufreq/intel_pstate.c:952
Inline: False
```
**Symbols:**

```
ffffffff816ea970-ffffffff816ea998: show_status (STB_LOCAL)
ffffffff8199e450-ffffffff8199e4cb: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff81708070)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1030)
Location: drivers/cpufreq/intel_pstate.c:1054
Inline: False
```
**Symbols:**

```
ffffffff81708070-ffffffff81708098: show_status (STB_LOCAL)
ffffffff819a1030-ffffffff819a10ab: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985b60)
Location: drivers/cpufreq/intel_pstate.c:1056
Inline: False
```
**Symbols:**

```
ffffffff81985b60-ffffffff81985bdb: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2f7f0)
Location: drivers/cpufreq/intel_pstate.c:1156
Inline: False
```
**Symbols:**

```
ffffffff81a2f7f0-ffffffff81a2f86b: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9b360)
Location: drivers/cpufreq/intel_pstate.c:1189
Inline: False
```
**Symbols:**

```
ffffffff81b9b360-ffffffff81b9b3df: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3cc70)
Location: drivers/cpufreq/intel_pstate.c:1164
Inline: False
```
**Symbols:**

```
ffffffff81d3cc70-ffffffff81d3ccef: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7840)
Location: drivers/cpufreq/intel_pstate.c:1184
Inline: False
```
**Symbols:**

```
ffffffff81da7840-ffffffff81da78bf: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f740)
Location: drivers/cpufreq/intel_pstate.c:1208
Inline: False
```
**Symbols:**

```
ffffffff81e5f740-ffffffff81e5f7bf: show_status (STB_LOCAL)
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
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffff8000107a8558)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
**Symbols:**

```
ffff8000107a8558-ffff8000107a859c: show_status (STB_LOCAL)
```
</details>
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
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186fdc0)
Location: drivers/cpufreq/intel_pstate.c:945
Inline: False
```
**Symbols:**

```
ffffffff8186fdc0-ffffffff8186fe39: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t show_status(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839340)
Location: drivers/cpufreq/intel_pstate.c:945
Inline: False
```
**Symbols:**

```
ffffffff81839340-ffffffff818393b9: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff816315f0)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1670)
Location: drivers/cpufreq/intel_pstate.c:945
Inline: False
```
**Symbols:**

```
ffffffff816315f0-ffffffff81631618: show_status (STB_LOCAL)
ffffffff818c1670-ffffffff818c16e9: show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t show_status(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bgrt.c (ffffffff8164b930)
Location: drivers/acpi/bgrt.c:25
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd980)
Location: drivers/cpufreq/intel_pstate.c:945
Inline: False
```
**Symbols:**

```
ffffffff8164b930-ffffffff8164b958: show_status (STB_LOCAL)
ffffffff818dd980-ffffffff818dd9f9: show_status (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>generic</code> and <code>aws</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>generic</code> and <code>azure</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

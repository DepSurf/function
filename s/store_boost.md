# Function: <code>store_boost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b1730)
Location: drivers/cpufreq/cpufreq.c:482
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b628e)
Location: drivers/cpufreq/acpi-cpufreq.c:161
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
**Symbols:**

```
ffffffff816b1730-ffffffff816b181e: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81712c30)
Location: drivers/cpufreq/cpufreq.c:536
Inline: False
```
**Symbols:**

```
ffffffff81712c30-ffffffff81712d1a: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81743ce0)
Location: drivers/cpufreq/cpufreq.c:536
Inline: False
```
**Symbols:**

```
ffffffff81743ce0-ffffffff81743dca: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81762360)
Location: drivers/cpufreq/cpufreq.c:536
Inline: False
```
**Symbols:**

```
ffffffff81762360-ffffffff8176245d: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d8350)
Location: drivers/cpufreq/cpufreq.c:568
Inline: False
```
**Symbols:**

```
ffffffff817d8350-ffffffff817d844d: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:553
Inline: False
```
**Symbols:**

```
ffffffff81820ca0-ffffffff81820d6b: store_boost (STB_LOCAL)
ffffffff81823173-ffffffff818231a8: store_boost.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:553
Inline: False
```
**Symbols:**

```
ffffffff8184cb50-ffffffff8184cc1b: store_boost (STB_LOCAL)
ffffffff8184f033-ffffffff8184f068: store_boost.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:583
Inline: False
```
**Symbols:**

```
ffffffff8188fbd0-ffffffff8188fc9b: store_boost (STB_LOCAL)
ffffffff81892456-ffffffff8189248b: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffffffff818c1dd0-ffffffff818c1e9b: store_boost (STB_LOCAL)
ffffffff818c4517-ffffffff818c454c: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:591
Inline: False
```
**Symbols:**

```
ffffffff81994000-ffffffff819940ca: store_boost (STB_LOCAL)
ffffffff81996771-ffffffff819967a6: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:598
Inline: False
```
**Symbols:**

```
ffffffff81997360-ffffffff8199742a: store_boost (STB_LOCAL)
ffffffff81c29802-ffffffff81c29837: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:595
Inline: False
```
**Symbols:**

```
ffffffff8197e6a0-ffffffff8197e754: store_boost (STB_LOCAL)
ffffffff81c1bcf3-ffffffff81c1bd28: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:596
Inline: False
```
**Symbols:**

```
ffffffff81a27820-ffffffff81a278d1: store_boost (STB_LOCAL)
ffffffff81d2c16e-ffffffff81d2c1a3: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:597
Inline: False
```
**Symbols:**

```
ffffffff81b915b0-ffffffff81b9166a: store_boost (STB_LOCAL)
ffffffff81ef8410-ffffffff81ef8445: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d318e0)
Location: drivers/cpufreq/cpufreq.c:597
Inline: False
```
**Symbols:**

```
ffffffff81d318e0-ffffffff81d319cc: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d9aca0)
Location: drivers/cpufreq/cpufreq.c:604
Inline: False
```
**Symbols:**

```
ffffffff81d9aca0-ffffffff81d9ad8c: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e52a20)
Location: drivers/cpufreq/cpufreq.c:605
Inline: False
```
**Symbols:**

```
ffffffff81e52a20-ffffffff81e52b0c: store_boost (STB_LOCAL)
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
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1fa78)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffff800010b1fa78-ffff800010b1fba0: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfa878)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
c0bfa878-c0bfa9a8: store_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c13df0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
c000000000c13df0-c000000000c13f30: store_boost (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffffffff818664f0-ffffffff818665bb: store_boost (STB_LOCAL)
ffffffff81868c37-ffffffff81868c6c: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffffffff8182f1a0-ffffffff8182f26b: store_boost (STB_LOCAL)
ffffffff818318e7-ffffffff8183191c: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffffffff818b7280-ffffffff818b734b: store_boost (STB_LOCAL)
ffffffff818b99c7-ffffffff818b99fc: store_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t store_boost(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:586
Inline: False
```
**Symbols:**

```
ffffffff818d3e70-ffffffff818d3f3b: store_boost (STB_LOCAL)
ffffffff818d5d2e-ffffffff818d5d63: store_boost.cold (STB_LOCAL)
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

# Function: <code>governor_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t governor_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ec4b0)
Location: drivers/devfreq/devfreq.c:770
Inline: False
```
**Symbols:**

```
ffffffff816ec4b0-ffffffff816ec4e4: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81717440)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81751200)
Location: drivers/devfreq/devfreq.c:901
Inline: False
```
**Symbols:**

```
ffffffff81717440-ffffffff81717454: governor_show (STB_LOCAL)
ffffffff81751200-ffffffff81751234: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81749220)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8177cf80)
Location: drivers/devfreq/devfreq.c:913
Inline: False
```
**Symbols:**

```
ffffffff81749220-ffffffff81749234: governor_show (STB_LOCAL)
ffffffff8177cf80-ffffffff8177cfb4: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff817678b0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8179bb10)
Location: drivers/devfreq/devfreq.c:908
Inline: False
```
**Symbols:**

```
ffffffff817678b0-ffffffff817678c4: governor_show (STB_LOCAL)
ffffffff8179bb10-ffffffff8179bb44: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff817dd780)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81812ac0)
Location: drivers/devfreq/devfreq.c:969
Inline: False
```
**Symbols:**

```
ffffffff817dd780-ffffffff817dd797: governor_show (STB_LOCAL)
ffffffff81812ac0-ffffffff81812af4: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81826420)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8185c960)
Location: drivers/devfreq/devfreq.c:972
Inline: False
```
**Symbols:**

```
ffffffff81826420-ffffffff81826437: governor_show (STB_LOCAL)
ffffffff8185c960-ffffffff8185c994: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81852300)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8187bf10)
Location: drivers/devfreq/devfreq.c:1101
Inline: False
```
**Symbols:**

```
ffffffff81852300-ffffffff81852317: governor_show (STB_LOCAL)
ffffffff8187bf10-ffffffff8187bf44: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81895870)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff818c6090)
Location: drivers/devfreq/devfreq.c:1114
Inline: False
```
**Symbols:**

```
ffffffff81895870-ffffffff8189588a: governor_show (STB_LOCAL)
ffffffff818c6090-ffffffff818c60c7: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818c7880)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff818f83f0)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffff818c7880-ffffffff818c789a: governor_show (STB_LOCAL)
ffffffff818f83f0-ffffffff818f8427: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81999a40)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce8a0)
Location: drivers/devfreq/devfreq.c:1268
Inline: False
```
**Symbols:**

```
ffffffff81999a40-ffffffff81999a5a: governor_show (STB_LOCAL)
ffffffff819ce8a0-ffffffff819ce8d7: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff8199cad0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce220)
Location: drivers/devfreq/devfreq.c:1349
Inline: False
```
**Symbols:**

```
ffffffff8199cad0-ffffffff8199caea: governor_show (STB_LOCAL)
ffffffff819ce220-ffffffff819ce257: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff819817a0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819b3390)
Location: drivers/devfreq/devfreq.c:1367
Inline: False
```
**Symbols:**

```
ffffffff819817a0-ffffffff819817ba: governor_show (STB_LOCAL)
ffffffff819b3390-ffffffff819b33c7: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81a2aad0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81a61c70)
Location: drivers/devfreq/devfreq.c:1367
Inline: False
```
**Symbols:**

```
ffffffff81a2aad0-ffffffff81a2aaea: governor_show (STB_LOCAL)
ffffffff81a61c70-ffffffff81a61ca7: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81b94e40)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:16
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd2a80)
Location: drivers/devfreq/devfreq.c:1397
Inline: False
```
**Symbols:**

```
ffffffff81b94e40-ffffffff81b94e64: governor_show (STB_LOCAL)
ffffffff81bd2a80-ffffffff81bd2acb: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81d357c0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:16
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7e880)
Location: drivers/devfreq/devfreq.c:1399
Inline: False
```
**Symbols:**

```
ffffffff81d357c0-ffffffff81d357e4: governor_show (STB_LOCAL)
ffffffff81d7e880-ffffffff81d7e8cb: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81d9eb30)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:16
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81decc10)
Location: drivers/devfreq/devfreq.c:1400
Inline: False
```
**Symbols:**

```
ffffffff81d9eb30-ffffffff81d9eb54: governor_show (STB_LOCAL)
ffffffff81decc10-ffffffff81decc5b: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81e56940)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:16
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea2fb0)
Location: drivers/devfreq/devfreq.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81e56940-ffffffff81e56964: governor_show (STB_LOCAL)
ffffffff81ea2fb0-ffffffff81ea2ffb: governor_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffff800010b25c90)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffff800010b84d70)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffff800010b25c90-ffff800010b25cd4: governor_show (STB_LOCAL)
ffff800010b84d70-ffff800010b84dc0: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (c0bffbac)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (c0c67dec)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
c0bffbac-c0bffbd0: governor_show (STB_LOCAL)
c0c67dec-c0c67e2c: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (c000000000c1aee0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (c000000000c62990)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
c000000000c1aee0-c000000000c1af24: governor_show (STB_LOCAL)
c000000000c62990-c000000000c629e8: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t governor_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072e3ee)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffe00072e3ee-ffffffe00072e432: governor_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff8186bfa0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81899720)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8186bfa0-ffffffff8186bfba: governor_show (STB_LOCAL)
ffffffff81899720-ffffffff81899757: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81834c50)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81856bf0)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffff81834c50-ffffffff81834c6a: governor_show (STB_LOCAL)
ffffffff81856bf0-ffffffff81856c27: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818bcd30)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff818e8e10)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffff818bcd30-ffffffff818bcd4a: governor_show (STB_LOCAL)
ffffffff818e8e10-ffffffff818e8e47: governor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t governor_show(struct kobject *kobj, struct attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818d9020)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:21
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81909e90)
Location: drivers/devfreq/devfreq.c:1121
Inline: False
```
**Symbols:**

```
ffffffff818d9020-ffffffff818d903a: governor_show (STB_LOCAL)
ffffffff81909e90-ffffffff81909ec7: governor_show (STB_LOCAL)
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
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct attribute *attr</code>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct attribute *attr</code> ➡️ <code>struct device_attribute *attr</code>
</li>
</ul>
</details>
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

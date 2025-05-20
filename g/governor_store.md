# Function: <code>governor_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t governor_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ecf10)
Location: drivers/devfreq/devfreq.c:779
Inline: False
```
**Symbols:**

```
ffffffff816ecf10-ffffffff816ed08c: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81717460)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81751de0)
Location: drivers/devfreq/devfreq.c:910
Inline: False
```
**Symbols:**

```
ffffffff81717460-ffffffff817174cb: governor_store (STB_LOCAL)
ffffffff81751de0-ffffffff81751f5c: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81749240)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8177dbb0)
Location: drivers/devfreq/devfreq.c:922
Inline: False
```
**Symbols:**

```
ffffffff81749240-ffffffff817492ab: governor_store (STB_LOCAL)
ffffffff8177dbb0-ffffffff8177dd4b: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81767920)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8179c6f0)
Location: drivers/devfreq/devfreq.c:917
Inline: False
```
**Symbols:**

```
ffffffff81767920-ffffffff8176798d: governor_store (STB_LOCAL)
ffffffff8179c6f0-ffffffff8179c897: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff817dd7f0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81812f70)
Location: drivers/devfreq/devfreq.c:978
Inline: False
```
**Symbols:**

```
ffffffff817dd7f0-ffffffff817dd862: governor_store (STB_LOCAL)
ffffffff81812f70-ffffffff81813135: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81826490)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8185ce50)
Location: drivers/devfreq/devfreq.c:981
Inline: False
```
**Symbols:**

```
ffffffff81826490-ffffffff818264ff: governor_store (STB_LOCAL)
ffffffff8185ce50-ffffffff8185d010: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81852320)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:32
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff8187ce40)
Location: drivers/devfreq/devfreq.c:1110
Inline: False
```
**Symbols:**

```
ffffffff81852320-ffffffff8185238f: governor_store (STB_LOCAL)
ffffffff8187ce40-ffffffff8187d000: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81895890)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81895890-ffffffff81895902: governor_store (STB_LOCAL)
ffffffff818c63d0-ffffffff818c6544: governor_store (STB_LOCAL)
ffffffff818c7b5b-ffffffff818c7c36: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818c78a0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffff818c78a0-ffffffff818c7912: governor_store (STB_LOCAL)
ffffffff818f94e0-ffffffff818f9654: governor_store (STB_LOCAL)
ffffffff818fa040-ffffffff818fa11b: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81999a60)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1277
Inline: False
```
**Symbols:**

```
ffffffff81999a60-ffffffff81999ad2: governor_store (STB_LOCAL)
ffffffff819cf310-ffffffff819cf484: governor_store (STB_LOCAL)
ffffffff819d0a6f-ffffffff819d0b4a: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff8199caf0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1360
Inline: False
```
**Symbols:**

```
ffffffff8199caf0-ffffffff8199cb62: governor_store (STB_LOCAL)
ffffffff819cef70-ffffffff819cf120: governor_store (STB_LOCAL)
ffffffff81c2f3ad-ffffffff81c2f469: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff819817c0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1378
Inline: False
```
**Symbols:**

```
ffffffff819817c0-ffffffff81981832: governor_store (STB_LOCAL)
ffffffff819b40d0-ffffffff819b4280: governor_store (STB_LOCAL)
ffffffff81c21672-ffffffff81c2172e: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81a2aaf0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1378
Inline: False
```
**Symbols:**

```
ffffffff81a2aaf0-ffffffff81a2ab62: governor_store (STB_LOCAL)
ffffffff81a62cb0-ffffffff81a62e60: governor_store (STB_LOCAL)
ffffffff81d331db-ffffffff81d33297: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81b94e70)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1408
Inline: False
```
**Symbols:**

```
ffffffff81b94e70-ffffffff81b94ee9: governor_store (STB_LOCAL)
ffffffff81bd4150-ffffffff81bd4329: governor_store (STB_LOCAL)
ffffffff81eff676-ffffffff81eff735: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81d35800)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81d81410)
Location: drivers/devfreq/devfreq.c:1410
Inline: False
```
**Symbols:**

```
ffffffff81d35800-ffffffff81d35879: governor_store (STB_LOCAL)
ffffffff81d81410-ffffffff81d8170b: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81d9eb70)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81def7d0)
Location: drivers/devfreq/devfreq.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81d9eb70-ffffffff81d9ebe9: governor_store (STB_LOCAL)
ffffffff81def7d0-ffffffff81defac3: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81e56980)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:24
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5d90)
Location: drivers/devfreq/devfreq.c:1432
Inline: False
```
**Symbols:**

```
ffffffff81e56980-ffffffff81e569f9: governor_store (STB_LOCAL)
ffffffff81ea5d90-ffffffff81ea6083: governor_store (STB_LOCAL)
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
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffff800010b25cd8)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffff800010b852f8)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffff800010b25cd8-ffff800010b25d74: governor_store (STB_LOCAL)
ffff800010b852f8-ffff800010b85518: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (c0bffbd0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (c0c69390)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
c0bffbd0-c0bffc3c: governor_store (STB_LOCAL)
c0c69390-c0c695a8: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (c000000000c1af30)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (c000000000c64650)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
c000000000c1af30-c000000000c1b028: governor_store (STB_LOCAL)
c000000000c64650-c000000000c64968: governor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t governor_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072efe0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffe00072efe0-ffffffe00072f194: governor_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff8186bfc0)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffff8186bfc0-ffffffff8186c032: governor_store (STB_LOCAL)
ffffffff8189a810-ffffffff8189a984: governor_store (STB_LOCAL)
ffffffff8189b370-ffffffff8189b44b: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff81834c70)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffff81834c70-ffffffff81834ce2: governor_store (STB_LOCAL)
ffffffff81857ce0-ffffffff81857e54: governor_store (STB_LOCAL)
ffffffff81858840-ffffffff8185891b: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818bcd50)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffff818bcd50-ffffffff818bcdc2: governor_store (STB_LOCAL)
ffffffff818e9f00-ffffffff818ea074: governor_store (STB_LOCAL)
ffffffff818eaa60-ffffffff818eab3b: governor_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t governor_store(struct kobject *kobj, struct attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_governor_attr_set.c (ffffffff818d9040)
Location: drivers/cpufreq/cpufreq_governor_attr_set.c:29
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1130
Inline: False
```
**Symbols:**

```
ffffffff818d9040-ffffffff818d90b2: governor_store (STB_LOCAL)
ffffffff8190af80-ffffffff8190b0f4: governor_store (STB_LOCAL)
ffffffff8190bae0-ffffffff8190bbbb: governor_store.cold (STB_LOCAL)
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

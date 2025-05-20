# Function: <code>store_no_turbo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff816bad40)
Location: drivers/cpufreq/intel_pstate.c:417
Inline: False
```
**Symbols:**

```
ffffffff816bad40-ffffffff816bae2c: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171cb00)
Location: drivers/cpufreq/intel_pstate.c:699
Inline: False
```
**Symbols:**

```
ffffffff8171cb00-ffffffff8171cbf1: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174eee0)
Location: drivers/cpufreq/intel_pstate.c:1092
Inline: True
```
**Symbols:**

```
ffffffff8174eee0-ffffffff8174efd8: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176dd60)
Location: drivers/cpufreq/intel_pstate.c:1096
Inline: False
```
**Symbols:**

```
ffffffff8176dd60-ffffffff8176deae: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e3760)
Location: drivers/cpufreq/intel_pstate.c:911
Inline: False
```
**Symbols:**

```
ffffffff817e3760-ffffffff817e38ae: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c5a0)
Location: drivers/cpufreq/intel_pstate.c:942
Inline: False
```
**Symbols:**

```
ffffffff8182c5a0-ffffffff8182c6f2: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81858650)
Location: drivers/cpufreq/intel_pstate.c:1004
Inline: False
```
**Symbols:**

```
ffffffff81858650-ffffffff818587a2: store_no_turbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1041
Inline: False
```
**Symbols:**

```
ffffffff8189c190-ffffffff8189c2b6: store_no_turbo (STB_LOCAL)
ffffffff8189c640-ffffffff8189c674: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1040
Inline: False
```
**Symbols:**

```
ffffffff818ce480-ffffffff818ce5a6: store_no_turbo (STB_LOCAL)
ffffffff818ce95f-ffffffff818ce993: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1047
Inline: False
```
**Symbols:**

```
ffffffff819a02b0-ffffffff819a0430: store_no_turbo (STB_LOCAL)
ffffffff819a0e28-ffffffff819a0e40: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1149
Inline: False
```
**Symbols:**

```
ffffffff819a3010-ffffffff819a3190: store_no_turbo (STB_LOCAL)
ffffffff81c2a000-ffffffff81c2a018: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1151
Inline: False
```
**Symbols:**

```
ffffffff81987e20-ffffffff81987fa0: store_no_turbo (STB_LOCAL)
ffffffff81c1c3d6-ffffffff81c1c3ee: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1251
Inline: False
```
**Symbols:**

```
ffffffff81a31d10-ffffffff81a31e9d: store_no_turbo (STB_LOCAL)
ffffffff81d2cba5-ffffffff81d2cbd1: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1284
Inline: False
```
**Symbols:**

```
ffffffff81b9e020-ffffffff81b9e1ed: store_no_turbo (STB_LOCAL)
ffffffff81ef8ee7-ffffffff81ef8f27: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1259
Inline: False
```
**Symbols:**

```
ffffffff81d3f7b0-ffffffff81d3f96d: store_no_turbo (STB_LOCAL)
ffffffff820a91af-ffffffff820a91d7: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1279
Inline: False
```
**Symbols:**

```
ffffffff81daa320-ffffffff81daa4dd: store_no_turbo (STB_LOCAL)
ffffffff8212a5b8-ffffffff8212a5e0: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1303
Inline: False
```
**Symbols:**

```
ffffffff81e624a0-ffffffff81e6264b: store_no_turbo (STB_LOCAL)
ffffffff8220c377-ffffffff8220c3a0: store_no_turbo.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1040
Inline: False
```
**Symbols:**

```
ffffffff81872080-ffffffff818721a6: store_no_turbo (STB_LOCAL)
ffffffff8187255f-ffffffff81872593: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1040
Inline: False
```
**Symbols:**

```
ffffffff8183b5f0-ffffffff8183b73a: store_no_turbo (STB_LOCAL)
ffffffff8183c205-ffffffff8183c239: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1040
Inline: False
```
**Symbols:**

```
ffffffff818c3930-ffffffff818c3a56: store_no_turbo (STB_LOCAL)
ffffffff818c3e0f-ffffffff818c3e43: store_no_turbo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t store_no_turbo(struct kobject *a, struct kobj_attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1040
Inline: False
```
**Symbols:**

```
ffffffff818dfca0-ffffffff818dfdc6: store_no_turbo (STB_LOCAL)
ffffffff818e017f-ffffffff818e01b3: store_no_turbo.cold (STB_LOCAL)
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
<code>struct attribute *b</code> ➡️ <code>struct kobj_attribute *b</code>
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

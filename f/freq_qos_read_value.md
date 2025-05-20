# Function: <code>freq_qos_read_value</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811072c0)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff811072c0-ffffffff8110730a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111cc0)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81111cc0-ffffffff81111d0a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110ed90)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8110ed90-ffffffff8110edda: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f830)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8110f830-ffffffff8110f87a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112f180)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8112f180-ffffffff8112f1ca: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81150740)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81150740-ffffffff811507b2: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117f0e0)
Location: kernel/power/qos.c:461
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8117f0e0-ffffffff8117f152: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118fd30)
Location: kernel/power/qos.c:466
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8118fd30-ffffffff8118fda2: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e6f0)
Location: kernel/power/qos.c:471
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8119e6f0-ffffffff8119e762: freq_qos_read_value (STB_GLOBAL)
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
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016e1a8)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffff80001016e1a8-ffff80001016e230: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b9084)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
c03b9084-c03b9108: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c5b00)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
c0000000001c5b00-c0000000001c5b8c: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d680)
Location: kernel/power/qos.c:688
Inline: False
```
**Symbols:**

```
ffffffe00010d680-ffffffe00010d6f8: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811005d0)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff811005d0-ffffffff8110061a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f07c0)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff810f07c0-ffffffff810f080a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fd790)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff810fd790-ffffffff810fd7da: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 freq_qos_read_value(struct freq_constraints *qos, enum freq_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81108a50)
Location: kernel/power/qos.c:688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81108a50-ffffffff81108a9a: freq_qos_read_value (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

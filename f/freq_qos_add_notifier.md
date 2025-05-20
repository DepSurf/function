# Function: <code>freq_qos_add_notifier</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106540)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81106540-ffffffff81106591: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811112a0)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff811112a0-ffffffff811112f1: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e420)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8110e420-ffffffff8110e471: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110ef20)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8110ef20-ffffffff8110ef70: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112e7c0)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8112e7c0-ffffffff8112e810: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fb90)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8114fb90-ffffffff8114fc09: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e420)
Location: kernel/power/qos.c:615
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8117e420-ffffffff8117e499: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f080)
Location: kernel/power/qos.c:620
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8118f080-ffffffff8118f0f9: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119da30)
Location: kernel/power/qos.c:625
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8119da30-ffffffff8119daa9: freq_qos_add_notifier (STB_GLOBAL)
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
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016cbc0)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff80001016cbc0-ffff80001016cc6c: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b7ff4)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c03b7ff4-c03b8080: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4530)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0000000001c4530-c0000000001c45e8: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010c8f4)
Location: kernel/power/qos.c:840
Inline: True
```
**Symbols:**

```
ffffffe00010c8f4-ffffffe00010c980: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ff850)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff810ff850-ffffffff810ff8a1: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810efa40)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff810efa40-ffffffff810efa91: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fca10)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff810fca10-ffffffff810fca61: freq_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_add_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81107c40)
Location: kernel/power/qos.c:840
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81107c40-ffffffff81107c91: freq_qos_add_notifier (STB_GLOBAL)
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

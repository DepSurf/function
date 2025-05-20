# Function: <code>freq_qos_remove_notifier</code>

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
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811065a0)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff811065a0-ffffffff811065f1: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111300)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff81111300-ffffffff81111351: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e480)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8110e480-ffffffff8110e4d1: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110ef70)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8110ef70-ffffffff8110efc0: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112e810)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8112e810-ffffffff8112e860: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fc10)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8114fc10-ffffffff8114fc89: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e4b0)
Location: kernel/power/qos.c:648
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8117e4b0-ffffffff8117e529: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f110)
Location: kernel/power/qos.c:653
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8118f110-ffffffff8118f189: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119dac0)
Location: kernel/power/qos.c:658
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
**Symbols:**

```
ffffffff8119dac0-ffffffff8119db39: freq_qos_remove_notifier (STB_GLOBAL)
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
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016cc70)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffff80001016cc70-ffff80001016cd1c: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8080)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
c03b8080-c03b810c: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c45f0)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
c0000000001c45f0-c0000000001c46a8: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010c980)
Location: kernel/power/qos.c:873
Inline: True
```
**Symbols:**

```
ffffffe00010c980-ffffffe00010ca0c: freq_qos_remove_notifier (STB_GLOBAL)
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
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ff8b0)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff810ff8b0-ffffffff810ff901: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810efaa0)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff810efaa0-ffffffff810efaf1: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fca70)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff810fca70-ffffffff810fcac1: freq_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints *qos, enum freq_qos_req_type type, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81107ca0)
Location: kernel/power/qos.c:873
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff81107ca0-ffffffff81107cf1: freq_qos_remove_notifier (STB_GLOBAL)
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

# Function: <code>cpufreq_update_current_freq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710910)
Location: drivers/cpufreq/cpufreq.c:1575
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff81710910-ffffffff8171099b: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742920)
Location: drivers/cpufreq/cpufreq.c:1547
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff81742920-ffffffff817429a5: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81760fa0)
Location: drivers/cpufreq/cpufreq.c:1550
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff81760fa0-ffffffff81761025: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6f60)
Location: drivers/cpufreq/cpufreq.c:1582
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff817d6f60-ffffffff817d6feb: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81821060)
Location: drivers/cpufreq/cpufreq.c:1580
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff81821060-ffffffff818210eb: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int cpufreq_update_current_freq(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184cdd0)
Location: drivers/cpufreq/cpufreq.c:1581
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff8184cdd0-ffffffff8184ce5b: cpufreq_update_current_freq (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>

# Function: <code>get_governor</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81993e50)
Location: drivers/cpufreq/cpufreq.c:624
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81993e50-ffffffff81993ed1: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996e00)
Location: drivers/cpufreq/cpufreq.c:631
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81996e00-ffffffff81996e81: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197bef0)
Location: drivers/cpufreq/cpufreq.c:628
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff8197bef0-ffffffff8197bf71: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25160)
Location: drivers/cpufreq/cpufreq.c:629
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81a25160-ffffffff81a251e1: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ed70)
Location: drivers/cpufreq/cpufreq.c:630
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81b8ed70-ffffffff81b8edf8: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2e210)
Location: drivers/cpufreq/cpufreq.c:630
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81d2e210-ffffffff81d2e298: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d97480)
Location: drivers/cpufreq/cpufreq.c:637
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81d97480-ffffffff81d97508: get_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpufreq_governor *get_governor(const char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4f100)
Location: drivers/cpufreq/cpufreq.c:672
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81e4f100-ffffffff81e4f188: get_governor (STB_LOCAL)
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

# Function: <code>sugov_init</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4730)
Location: kernel/sched/cpufreq_schedutil.c:472
Inline: True
```
**Symbols:**

```
ffffffff810d4730-ffffffff810d4a97: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3b00)
Location: kernel/sched/cpufreq_schedutil.c:489
Inline: False
```
**Symbols:**

```
ffffffff810d3b00-ffffffff810d3e68: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db7d0)
Location: kernel/sched/cpufreq_schedutil.c:544
Inline: False
```
**Symbols:**

```
ffffffff810db7d0-ffffffff810dbb10: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:654
Inline: False
```
**Symbols:**

```
ffffffff810e3890-ffffffff810e3bc3: sugov_init (STB_LOCAL)
ffffffff810e4049-ffffffff810e4069: sugov_init.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:727
Inline: False
```
**Symbols:**

```
ffffffff810edea0-ffffffff810ee1d3: sugov_init (STB_LOCAL)
ffffffff810ee7c3-ffffffff810ee7e3: sugov_init.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:734
Inline: False
```
**Symbols:**

```
ffffffff810f4c50-ffffffff810f4f9d: sugov_init (STB_LOCAL)
ffffffff810f55d4-ffffffff810f560d: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff811008c0-ffffffff81100c19: sugov_init (STB_LOCAL)
ffffffff811012a8-ffffffff811012c8: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b1c0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff8110b1c0-ffffffff8110b3a4: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108080)
Location: kernel/sched/cpufreq_schedutil.c:762
Inline: False
```
**Symbols:**

```
ffffffff81108080-ffffffff81108264: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a1c0)
Location: kernel/sched/cpufreq_schedutil.c:649
Inline: False
```
**Symbols:**

```
ffffffff8110a1c0-ffffffff8110a3a2: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:656
Inline: False
```
**Symbols:**

```
ffffffff811287d0-ffffffff811289be: sugov_init (STB_LOCAL)
ffffffff81ca92c2-ffffffff81ca92d7: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:656
Inline: False
```
**Symbols:**

```
ffffffff811441b0-ffffffff811443a5: sugov_init (STB_LOCAL)
ffffffff81e57ed2-ffffffff81e57ee7: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:655
Inline: False
```
**Symbols:**

```
ffffffff81170ec0-ffffffff811710db: sugov_init (STB_LOCAL)
ffffffff82057f1f-ffffffff82057f34: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:659
Inline: False
```
**Symbols:**

```
ffffffff811816c0-ffffffff811818db: sugov_init (STB_LOCAL)
ffffffff820d66ae-ffffffff820d66c3: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:725
Inline: False
```
**Symbols:**

```
ffffffff8118fef0-ffffffff81190186: sugov_init (STB_LOCAL)
ffffffff821b18f8-ffffffff821b190d: sugov_init.cold (STB_LOCAL)
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
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010165090)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffff800010165090-ffff8000101653d4: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b16ac)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
c03b16ac-c03b1a1c: sugov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc240)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
c0000000001bc240-c0000000001bc6b8: sugov_init (STB_LOCAL)
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
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff810f9bd0-ffffffff810f9f29: sugov_init (STB_LOCAL)
ffffffff810fa5b8-ffffffff810fa5d8: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff810e9db0-ffffffff810ea109: sugov_init (STB_LOCAL)
ffffffff810ea798-ffffffff810ea7b8: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff810f6df0-ffffffff810f7149: sugov_init (STB_LOCAL)
ffffffff810f7778-ffffffff810f7798: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sugov_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:737
Inline: False
```
**Symbols:**

```
ffffffff81101e70-ffffffff811021c9: sugov_init (STB_LOCAL)
ffffffff81102856-ffffffff81102876: sugov_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

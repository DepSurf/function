# Function: <code>cpufreq_disable_fast_switch</code>

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
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817109a0)
Location: drivers/cpufreq/cpufreq.c:483
Inline: False
```
**Symbols:**

```
ffffffff817109a0-ffffffff817109fe: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817429b0)
Location: drivers/cpufreq/cpufreq.c:483
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
```
**Symbols:**

```
ffffffff817429b0-ffffffff81742a0e: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761030)
Location: drivers/cpufreq/cpufreq.c:483
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81761030-ffffffff8176107f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6ff0)
Location: drivers/cpufreq/cpufreq.c:489
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff817d6ff0-ffffffff817d703f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181fa10)
Location: drivers/cpufreq/cpufreq.c:474
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8181fa10-ffffffff8181fa5f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b8b0)
Location: drivers/cpufreq/cpufreq.c:474
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8184b8b0-ffffffff8184b8ff: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:504
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818923ab-ffffffff818923be: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff8188e910-ffffffff8188e95f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0880)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818c0880-ffffffff818c08cf: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81992630)
Location: drivers/cpufreq/cpufreq.c:512
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81992630-ffffffff81992682: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995840)
Location: drivers/cpufreq/cpufreq.c:518
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81995840-ffffffff81995892: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197a6b0)
Location: drivers/cpufreq/cpufreq.c:515
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8197a6b0-ffffffff8197a702: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:515
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81d2bd88-ffffffff81d2bd9d: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff81a23f50-ffffffff81a23fb2: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:516
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff81ef7fd8-ffffffff81ef7fed: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff81b8d5d0-ffffffff81b8d63c: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:516
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff820a8c71-ffffffff820a8c86: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff81d2ce40-ffffffff81d2ceac: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:523
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff82129e8a-ffffffff82129e9f: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff81d960b0-ffffffff81d9611c: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:524
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8220bc21-ffffffff8220bc36: cpufreq_disable_fast_switch.cold (STB_LOCAL)
ffffffff81e4dba0-ffffffff81e4dc0c: cpufreq_disable_fast_switch (STB_GLOBAL)
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
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1d198)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffff800010b1d198-ffff800010b1d204: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf80cc)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c0bf80cc-c0bf8148: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0ff20)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c000000000c0ff20-c000000000c0ffb4: cpufreq_disable_fast_switch (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864fa0)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81864fa0-ffffffff81864fef: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182dc50)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8182dc50-ffffffff8182dc9f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5d30)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818b5d30-ffffffff818b5d7f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_disable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1fe0)
Location: drivers/cpufreq/cpufreq.c:507
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818d1fe0-ffffffff818d202f: cpufreq_disable_fast_switch (STB_GLOBAL)
```
</details>
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

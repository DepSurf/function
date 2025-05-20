# Function: <code>distribute_cfs_runtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc180)
Location: kernel/sched/fair.c:3672
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
```
**Symbols:**

```
ffffffff810bc180-ffffffff810bc267: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf840)
Location: kernel/sched/fair.c:4010
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810bf840-ffffffff810bf927: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5700)
Location: kernel/sched/fair.c:4227
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810c5700-ffffffff810c57e7: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf2a0)
Location: kernel/sched/fair.c:4349
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810bf2a0-ffffffff810bf393: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6ac0)
Location: kernel/sched/fair.c:4688
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810c6ac0-ffffffff810c6bb3: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce9c0)
Location: kernel/sched/fair.c:4861
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810ce9c0-ffffffff810ceab3: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7f40)
Location: kernel/sched/fair.c:4555
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810d7f40-ffffffff810d8033: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df230)
Location: kernel/sched/fair.c:4661
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810df230-ffffffff810df363: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9970)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810e9970-ffffffff810e9a9c: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3fe0)
Location: kernel/sched/fair.c:4883
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810f3fe0-ffffffff810f4117: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2250)
Location: kernel/sched/fair.c:4929
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810f2250-ffffffff810f23b4: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4530)
Location: kernel/sched/fair.c:4992
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810f4530-ffffffff810f4694: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5023
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff8110deb0-ffffffff8110e05c: distribute_cfs_runtime (STB_LOCAL)
ffffffff81ca6664-ffffffff81ca6693: distribute_cfs_runtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5070
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff81129bb0-ffffffff81129d5d: distribute_cfs_runtime (STB_LOCAL)
ffffffff81e55e8c-ffffffff81e55ebe: distribute_cfs_runtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5464
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff811535b0-ffffffff8115375d: distribute_cfs_runtime (STB_LOCAL)
ffffffff820570ea-ffffffff8205711c: distribute_cfs_runtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5647
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff81162ed0-ffffffff811632fb: distribute_cfs_runtime (STB_LOCAL)
ffffffff820d586c-ffffffff820d591a: distribute_cfs_runtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool distribute_cfs_runtime(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5996
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff8116fb40-ffffffff81170033: distribute_cfs_runtime (STB_LOCAL)
ffffffff821b08b5-ffffffff821b097d: distribute_cfs_runtime.cold (STB_LOCAL)
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
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010149838)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffff800010149838-ffff8000101499d0: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03975cc)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
c03975cc-c0397778: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019b880)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
c00000000019b880-c00000000019ba18: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f374e)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffe0000f374e-ffffffe0000f3860: distribute_cfs_runtime (STB_LOCAL)
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
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3ad0)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810e3ad0-ffffffff810e3bfc: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d2c80)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810d2c80-ffffffff810d2dac: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dfea0)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810dfea0-ffffffff810dffcc: distribute_cfs_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 distribute_cfs_runtime(struct cfs_bandwidth *cfs_b, u64 remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eba30)
Location: kernel/sched/fair.c:4602
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810eba30-ffffffff810ebb50: distribute_cfs_runtime (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 expires</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 remaining</code>
</li>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

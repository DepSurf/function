# Function: <code>get_update_sysctl_factor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b2160)
Location: kernel/sched/fair.c:144
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sysctl
  - kernel/sched/fair.c:sched_proc_update_handler
```
**Symbols:**

```
ffffffff810b2160-ffffffff810b21aa: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4c30)
Location: kernel/sched/fair.c:144
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810b4c30-ffffffff810b4c7a: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc280)
Location: kernel/sched/fair.c:159
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810bc280-ffffffff810bc2be: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6ce0)
Location: kernel/sched/fair.c:161
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810b6ce0-ffffffff810b6d1e: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be050)
Location: kernel/sched/fair.c:163
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810be050-ffffffff810be08e: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5d80)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810c5d80-ffffffff810c5dbc: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce720)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810ce720-ffffffff810ce75c: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6ac0)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810d6ac0-ffffffff810d6b09: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e05f0)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810e05f0-ffffffff810e062d: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9d95)
Location: kernel/sched/fair.c:161
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sysctl
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
```
**Symbols:**

```
ffffffff810e8ac0-ffffffff810e8afd: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1201)
Location: kernel/sched/fair.c:159
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3505)
Location: kernel/sched/fair.c:166
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110cd65)
Location: kernel/sched/fair.c:166
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811288b5)
Location: kernel/sched/fair.c:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81151f85)
Location: kernel/sched/fair.c:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81161865)
Location: kernel/sched/fair.c:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116f945)
Location: kernel/sched/fair.c:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
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
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010140448)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffff800010140448-ffff8000101404a8: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0390268)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
c0390268-c03902cc: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000018f670)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
c00000000018f670-c00000000018f6d8: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000ee400)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffe0000ee400-ffffffe0000ee476: get_update_sysctl_factor (STB_LOCAL)
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
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da7a0)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810da7a0-ffffffff810da7dd: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c97b0)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810c97b0-ffffffff810c97ed: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6b20)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810d6b20-ffffffff810d6b5d: get_update_sysctl_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int get_update_sysctl_factor();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2430)
Location: kernel/sched/fair.c:148
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
**Symbols:**

```
ffffffff810e2430-ffffffff810e246d: get_update_sysctl_factor (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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

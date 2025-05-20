# Function: <code>cpuidle_governor_latency_req</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8182dda0)
Location: drivers/cpuidle/governor.c:103
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff8182dda0-ffffffff8182dde9: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81859f60)
Location: drivers/cpuidle/governor.c:109
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff81859f60-ffffffff81859fa9: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8189d8b0)
Location: drivers/cpuidle/governor.c:109
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8189d8b0-ffffffff8189d8ff: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818cfd40)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff818cfd40-ffffffff818cfd8f: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a23c0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff819a23c0-ffffffff819a240b: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a5380)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff819a5380-ffffffff819a53cb: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81989ff0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81989ff0-ffffffff8198a03b: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81a34950)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81a34950-ffffffff81a3499b: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81ba11b0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/haltpoll.c:haltpoll_select
```
**Symbols:**

```
ffffffff81ba11b0-ffffffff81ba1201: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81d42eb0)
Location: drivers/cpuidle/governor.c:109
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/haltpoll.c:haltpoll_select
```
**Symbols:**

```
ffffffff81d42eb0-ffffffff81d42f01: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81dad0d0)
Location: drivers/cpuidle/governor.c:109
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/haltpoll.c:haltpoll_select
```
**Symbols:**

```
ffffffff81dad0d0-ffffffff81dad121: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s64 cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81e65170)
Location: drivers/cpuidle/governor.c:109
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/haltpoll.c:haltpoll_select
```
**Symbols:**

```
ffffffff81e65170-ffffffff81e651c1: cpuidle_governor_latency_req (STB_GLOBAL)
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
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffff800010b28030)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffff800010b28030-ffff800010b28088: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (c0c02cc4)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
c0c02cc4-c0c02d18: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (c000000000c1f520)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
c000000000c1f520-c000000000c1f5cc: cpuidle_governor_latency_req (STB_GLOBAL)
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
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818737e0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff818737e0-ffffffff8187382f: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8183d5d0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8183d5d0-ffffffff8183d61f: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818c51f0)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff818c51f0-ffffffff818c523f: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818e1650)
Location: drivers/cpuidle/governor.c:110
Inline: False
Direct callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff818e1650-ffffffff818e169f: cpuidle_governor_latency_req (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>s64</code>
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

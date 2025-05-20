# Function: <code>tcf_action_update_stats</code>

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
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u32 packets, bool drop, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72260)
Location: net/sched/act_api.c:1062
Inline: False
```
**Symbols:**

```
ffffffff81a72260-ffffffff81a722d8: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7ae30)
Location: net/sched/act_api.c:1115
Inline: False
```
**Symbols:**

```
ffffffff81a7ae30-ffffffff81a7ae9f: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a63b80)
Location: net/sched/act_api.c:1125
Inline: False
```
**Symbols:**

```
ffffffff81a63b80-ffffffff81a63bf5: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1cf00)
Location: net/sched/act_api.c:1134
Inline: False
```
**Symbols:**

```
ffffffff81b1cf00-ffffffff81b1cf75: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4280)
Location: net/sched/act_api.c:1486
Inline: False
```
**Symbols:**

```
ffffffff81ca4280-ffffffff81ca4317: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e60bf0)
Location: net/sched/act_api.c:1512
Inline: False
```
**Symbols:**

```
ffffffff81e60bf0-ffffffff81e60c87: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebcc40)
Location: net/sched/act_api.c:1507
Inline: False
```
**Symbols:**

```
ffffffff81ebcc40-ffffffff81ebccd7: tcf_action_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_action_update_stats(struct tc_action *a, u64 bytes, u64 packets, u64 drops, bool hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f7fe40)
Location: net/sched/act_api.c:1535
Inline: False
```
**Symbols:**

```
ffffffff81f7fe40-ffffffff81f7fed7: tcf_action_update_stats (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 drops</code>
</li>
<li>
<b>Param removed. </b>
<code>bool drop</code>
</li>
<li>
<b>Param type changed. </b>
<code>u32 packets</code> ➡️ <code>u64 packets</code>
</li>
</ul>
</details>
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

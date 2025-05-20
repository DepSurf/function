# Function: <code>tcf_action_dump_terse</code>

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
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a74240)
Location: net/sched/act_api.c:770
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
**Symbols:**

```
ffffffff81a74240-ffffffff81a74303: tcf_action_dump_terse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:235
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81a7cf80-ffffffff81a7d0bd: tcf_action_dump_terse (STB_LOCAL)
ffffffff81c32288-ffffffff81c322a0: tcf_action_dump_terse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:246
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81a65ce0-ffffffff81a65e1c: tcf_action_dump_terse (STB_LOCAL)
ffffffff81c24571-ffffffff81c24589: tcf_action_dump_terse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:246
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81b1ef90-ffffffff81b1f0cc: tcf_action_dump_terse (STB_LOCAL)
ffffffff81d3930f-ffffffff81d39327: tcf_action_dump_terse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:484
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81ca6b50-ffffffff81ca6c9e: tcf_action_dump_terse (STB_LOCAL)
ffffffff81f05ac1-ffffffff81f05ad9: tcf_action_dump_terse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e63060)
Location: net/sched/act_api.c:485
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81e63060-ffffffff81e631c6: tcf_action_dump_terse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebf0f0)
Location: net/sched/act_api.c:478
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81ebf0f0-ffffffff81ebf256: tcf_action_dump_terse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_dump_terse(struct sk_buff *skb, struct tc_action *a, bool from_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f82270)
Location: net/sched/act_api.c:478
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81f82270-ffffffff81f823d6: tcf_action_dump_terse (STB_LOCAL)
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
<code>bool from_act</code>
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

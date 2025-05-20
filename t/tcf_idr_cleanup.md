# Function: <code>tcf_idr_cleanup</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action *a, struct nlattr *est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81881750)
Location: net/sched/act_api.c:263
Inline: False
```
**Symbols:**

```
ffffffff81881750-ffffffff81881779: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81901ce0)
Location: net/sched/act_api.c:441
Inline: False
```
**Symbols:**

```
ffffffff81901ce0-ffffffff81901d1f: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff819655b4-ffffffff819655c7: tcf_idr_cleanup.cold (STB_LOCAL)
ffffffff81962e60-ffffffff81962e9e: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819999c0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff819999c0-ffffffff81999a09: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72310)
Location: net/sched/act_api.c:483
Inline: False
```
**Symbols:**

```
ffffffff81a72310-ffffffff81a72359: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7aef0)
Location: net/sched/act_api.c:524
Inline: False
```
**Symbols:**

```
ffffffff81a7aef0-ffffffff81a7af39: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a63c50)
Location: net/sched/act_api.c:537
Inline: False
```
**Symbols:**

```
ffffffff81a63c50-ffffffff81a63c99: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1cfd0)
Location: net/sched/act_api.c:537
Inline: False
```
**Symbols:**

```
ffffffff81b1cfd0-ffffffff81b1d019: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4450)
Location: net/sched/act_api.c:783
Inline: False
```
**Symbols:**

```
ffffffff81ca4450-ffffffff81ca44ad: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e60e00)
Location: net/sched/act_api.c:809
Inline: False
```
**Symbols:**

```
ffffffff81e60e00-ffffffff81e60e5d: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebce10)
Location: net/sched/act_api.c:804
Inline: False
```
**Symbols:**

```
ffffffff81ebce10-ffffffff81ebce6d: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80010)
Location: net/sched/act_api.c:804
Inline: False
```
**Symbols:**

```
ffffffff81f80010-ffffffff81f8006d: tcf_idr_cleanup (STB_GLOBAL)
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
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c467e0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffff800010c467e0-ffff800010c46848: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d5772c)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
c0d5772c-c0d5778c: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d42ef0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
c000000000d42ef0-c000000000d42f64: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b49dc)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffe0007b49dc-ffffffe0007b4a34: tcf_idr_cleanup (STB_GLOBAL)
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
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81939830)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff81939830-ffffffff81939879: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3330)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff818f3330-ffffffff818f3379: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198a9c0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff8198a9c0-ffffffff8198aa09: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_idr_cleanup(struct tc_action_net *tn, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ad1b0)
Location: net/sched/act_api.c:467
Inline: False
```
**Symbols:**

```
ffffffff819ad1b0-ffffffff819ad1f9: tcf_idr_cleanup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

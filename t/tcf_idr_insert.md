# Function: <code>tcf_idr_insert</code>

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
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81881800)
Location: net/sched/act_api.c:348
Inline: False
```
**Symbols:**

```
ffffffff81881800-ffffffff81881838: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5710)
Location: net/sched/act_api.c:368
Inline: False
```
**Symbols:**

```
ffffffff818d5710-ffffffff818d574a: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81901d90)
Location: net/sched/act_api.c:428
Inline: False
```
**Symbols:**

```
ffffffff81901d90-ffffffff81901dd4: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff819655c7-ffffffff819655da: tcf_idr_insert.cold (STB_LOCAL)
ffffffff81962f10-ffffffff81962f56: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81999a80)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff81999a80-ffffffff81999ad2: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72380)
Location: net/sched/act_api.c:470
Inline: False
```
**Symbols:**

```
ffffffff81a72380-ffffffff81a723d2: tcf_idr_insert (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c468f8)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffff800010c468f8-ffff800010c46964: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d57800)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
c0d57800-c0d57864: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d43050)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
c000000000d43050-c000000000d430d0: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b4b7e)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffe0007b4b7e-ffffffe0007b4bd8: tcf_idr_insert (STB_GLOBAL)
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
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819398f0)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff819398f0-ffffffff81939942: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f33f0)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff818f33f0-ffffffff818f3442: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198aa80)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff8198aa80-ffffffff8198aad2: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_idr_insert(struct tc_action_net *tn, struct tc_action *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ad270)
Location: net/sched/act_api.c:454
Inline: False
```
**Symbols:**

```
ffffffff819ad270-ffffffff819ad2c2: tcf_idr_insert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

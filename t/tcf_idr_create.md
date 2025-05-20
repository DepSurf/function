# Function: <code>tcf_idr_create</code>

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
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818820e0)
Location: net/sched/act_api.c:271
Inline: False
```
**Symbols:**

```
ffffffff818820e0-ffffffff8188236e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5820)
Location: net/sched/act_api.c:301
Inline: False
```
**Symbols:**

```
ffffffff818d5820-ffffffff818d5a26: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81902400)
Location: net/sched/act_api.c:374
Inline: False
```
**Symbols:**

```
ffffffff81902400-ffffffff81902636: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81963680)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff81963680-ffffffff8196388e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199a200)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff8199a200-ffffffff8199a40e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a728a0)
Location: net/sched/act_api.c:404
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81a728a0-ffffffff81a72abb: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b460)
Location: net/sched/act_api.c:456
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81a7b460-ffffffff81a7b67b: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a641e0)
Location: net/sched/act_api.c:468
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81a641e0-ffffffff81a6440c: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1d580)
Location: net/sched/act_api.c:468
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81b1d580-ffffffff81b1d811: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4b60)
Location: net/sched/act_api.c:712
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81ca4b60-ffffffff81ca4de8: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e61920)
Location: net/sched/act_api.c:738
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81e61920-ffffffff81e61bc2: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebddd0)
Location: net/sched/act_api.c:733
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81ebddd0-ffffffff81ebe072: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80fe0)
Location: net/sched/act_api.c:733
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_create_from_flags
```
**Symbols:**

```
ffffffff81f80fe0-ffffffff81f81282: tcf_idr_create (STB_GLOBAL)
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
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c46c90)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffff800010c46c90-ffff800010c46e88: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d57e54)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
c0d57e54-c0d58094: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d44190)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
c000000000d44190-c000000000d4447c: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b5208)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffe0007b5208-ffffffe0007b53a6: tcf_idr_create (STB_GLOBAL)
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
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193a070)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff8193a070-ffffffff8193a27e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3b70)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff818f3b70-ffffffff818f3d7e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198b200)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff8198b200-ffffffff8198b40e: tcf_idr_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_idr_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ada70)
Location: net/sched/act_api.c:400
Inline: False
```
**Symbols:**

```
ffffffff819ada70-ffffffff819adc7e: tcf_idr_create (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
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

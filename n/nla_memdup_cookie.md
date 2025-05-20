# Function: <code>nla_memdup_cookie</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_memdup_cookie(struct tc_action *a, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e46d0)
Location: net/sched/act_api.c:535
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff817e46d0-ffffffff817e4760: nla_memdup_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804279)
Location: net/sched/act_api.c:586
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81882f8e)
Location: net/sched/act_api.c:602
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d6bbc)
Location: net/sched/act_api.c:622
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81902e2e)
Location: net/sched/act_api.c:787
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81964028)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199aaf2)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tc_cookie *nla_memdup_cookie(struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72b60)
Location: net/sched/act_api.c:865
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81a72b60-ffffffff81a72bd5: nla_memdup_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tc_cookie *nla_memdup_cookie(struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b720)
Location: net/sched/act_api.c:871
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81a7b720-ffffffff81a7b795: nla_memdup_cookie (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff81a65732)
Location: net/sched/act_api.c:884
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/act_api.c (ffffffff81b1e8e7)
Location: net/sched/act_api.c:893
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/act_api.c (ffffffff81ca6374)
Location: net/sched/act_api.c:1214
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/act_api.c (ffffffff81e62854)
Location: net/sched/act_api.c:1240
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/act_api.c (ffffffff81ebe8e4)
Location: net/sched/act_api.c:1235
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/act_api.c (ffffffff81f81a5b)
Location: net/sched/act_api.c:1266
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c47d40)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58d90)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d44e44)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b588a)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193a962)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f4462)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198baf2)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ae362)
Location: net/sched/act_api.c:818
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>

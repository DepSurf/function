# Function: <code>free_tcf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_tcf(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81746e00)
Location: net/sched/act_api.c:30
Inline: False
```
**Symbols:**

```
ffffffff81746e00-ffffffff81746e2b: free_tcf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_tcf(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b40c0)
Location: net/sched/act_api.c:30
Inline: False
```
**Symbols:**

```
ffffffff817b40c0-ffffffff817b40ee: free_tcf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_tcf(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3940)
Location: net/sched/act_api.c:31
Inline: False
```
**Symbols:**

```
ffffffff817e3940-ffffffff817e398f: free_tcf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_tcf(struct callback_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81803330)
Location: net/sched/act_api.c:56
Inline: False
```
**Symbols:**

```
ffffffff81803330-ffffffff8180338d: free_tcf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_tcf(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818816e0)
Location: net/sched/act_api.c:63
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_cleanup
```
**Symbols:**

```
ffffffff818816e0-ffffffff81881741: free_tcf (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff818d5154)
Location: net/sched/act_api.c:63
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_idr_release
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
In net/sched/act_api.c (ffffffff81901c77)
Location: net/sched/act_api.c:79
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81962deb)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff8199994b)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72c0e)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81a7b7ce)
Location: net/sched/act_api.c:117
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81a644de)
Location: net/sched/act_api.c:117
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81b1d8ee)
Location: net/sched/act_api.c:117
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81ca5608)
Location: net/sched/act_api.c:119
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81e62108)
Location: net/sched/act_api.c:120
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81ebda58)
Location: net/sched/act_api.c:120
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81f80b48)
Location: net/sched/act_api.c:120
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffff800010c46794)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (c0d581c8)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (c000000000d42e44)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffe0007b48e8)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff819397bb)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff818f32bb)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff8198a94b)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff819ad13b)
Location: net/sched/act_api.c:101
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_cleanup
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tc_action *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct callback_head *head</code>
</li>
</ul>
</details>
</li>
</ul>

# Function: <code>tcf_idr_delete_index</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81903c91)
Location: net/sched/act_api.c:341
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff81964e00)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff8199b974)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_idr_delete_index(struct tcf_idrinfo *idrinfo, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72d90)
Location: net/sched/act_api.c:371
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
```
**Symbols:**

```
ffffffff81a72d90-ffffffff81a72e69: tcf_idr_delete_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_idr_delete_index(struct tcf_idrinfo *idrinfo, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b950)
Location: net/sched/act_api.c:423
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
```
**Symbols:**

```
ffffffff81a7b950-ffffffff81a7ba29: tcf_idr_delete_index (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff81a647d8)
Location: net/sched/act_api.c:435
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_delete
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
In net/sched/act_api.c (ffffffff81b1f7f2)
Location: net/sched/act_api.c:435
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
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
In net/sched/act_api.c (ffffffff81ca764f)
Location: net/sched/act_api.c:679
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
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
In net/sched/act_api.c (ffffffff81e6438f)
Location: net/sched/act_api.c:705
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
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
In net/sched/act_api.c (ffffffff81ebe1d8)
Location: net/sched/act_api.c:700
Inline: True
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
In net/sched/act_api.c (ffffffff81f813e8)
Location: net/sched/act_api.c:700
Inline: True
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
In net/sched/act_api.c (ffff800010c48b84)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (c0d59ba8)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (c000000000d46210)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffe0007b642c)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff8193b7e4)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff818f52e4)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff8198c974)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff819af204)
Location: net/sched/act_api.c:367
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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

# Function: <code>tcf_action_delete</code>

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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1195
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1211
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff81a749aa)
Location: net/sched/act_api.c:1307
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
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
In net/sched/act_api.c (ffffffff81a7d7aa)
Location: net/sched/act_api.c:1358
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_action_delete(struct net *net, struct tc_action **actions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a64780)
Location: net/sched/act_api.c:1368
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a64780-ffffffff81a648b5: tcf_action_delete (STB_LOCAL)
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1375
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1731
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1757
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebe180)
Location: net/sched/act_api.c:1754
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81ebe180-ffffffff81ebe2c6: tcf_action_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff81f81390)
Location: net/sched/act_api.c:1782
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81f81390-ffffffff81f814d6: tcf_action_delete.isra.0 (STB_LOCAL)
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1214
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
</ul>

# Function: <code>tc_cleanup_offload_action</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tc_cleanup_offload_action(struct flow_action *flow_action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca4188)
Location: net/sched/cls_api.c:3501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81c9d860-ffffffff81c9d8d4: tc_cleanup_offload_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tc_cleanup_offload_action(struct flow_action *flow_action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e60ac8)
Location: net/sched/cls_api.c:3501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81e59e70-ffffffff81e59ee4: tc_cleanup_offload_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tc_cleanup_offload_action(struct flow_action *flow_action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebca64)
Location: net/sched/cls_api.c:3708
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81eb5860-ffffffff81eb58c8: tc_cleanup_offload_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tc_cleanup_offload_action(struct flow_action *flow_action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7fc64)
Location: net/sched/cls_api.c:3764
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81f78570-ffffffff81f785d8: tc_cleanup_offload_action (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

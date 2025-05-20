# Function: <code>init_srcu_struct_nodes</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f107f)
Location: kernel/rcu/srcutree.c:61
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff810fae0d)
Location: kernel/rcu/srcutree.c:62
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff811032bd)
Location: kernel/rcu/srcutree.c:89
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff8110ec6d)
Location: kernel/rcu/srcutree.c:95
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff811182fe)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff811246ce)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_srcu_struct_nodes(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81131d60)
Location: kernel/rcu/srcutree.c:96
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff81131d60-ffffffff811320c6: init_srcu_struct_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_srcu_struct_nodes(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d540)
Location: kernel/rcu/srcutree.c:83
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff8112d540-ffffffff8112d89f: init_srcu_struct_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_srcu_struct_nodes(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112db60)
Location: kernel/rcu/srcutree.c:83
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff8112db60-ffffffff8112dec9: init_srcu_struct_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_srcu_struct_nodes(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:83
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff8114ee60-ffffffff8114f374: init_srcu_struct_nodes (STB_LOCAL)
ffffffff81cae28f-ffffffff81cae2ae: init_srcu_struct_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct *ssp, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff81175fa0-ffffffff8117650c: init_srcu_struct_nodes (STB_LOCAL)
ffffffff81e5e8b1-ffffffff81e5e8e7: init_srcu_struct_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct *ssp, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff811ad980-ffffffff811adf10: init_srcu_struct_nodes (STB_LOCAL)
ffffffff82059ed9-ffffffff82059f07: init_srcu_struct_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct *ssp, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff811bf9d0-ffffffff811bff23: init_srcu_struct_nodes (STB_LOCAL)
ffffffff820d86e5-ffffffff820d8713: init_srcu_struct_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct *ssp, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
**Symbols:**

```
ffffffff811cfe40-ffffffff811d0392: init_srcu_struct_nodes (STB_LOCAL)
ffffffff821b39af-ffffffff821b39dd: init_srcu_struct_nodes.cold (STB_LOCAL)
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
In kernel/rcu/srcutree.c (ffff800010189c40)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (c03d86e8)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (c0000000001e43c0)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffe00011ee3c)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff8111ccae)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff8110dd6e)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff8111ab9e)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
In kernel/rcu/srcutree.c (ffffffff8112647e)
Location: kernel/rcu/srcutree.c:83
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_static</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

# Function: <code>rcu_exp_need_qs</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a510)
Location: kernel/rcu/tree_exp.h:702
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff8111a510-ffffffff8111a54d: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126910)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff81126910-ffffffff8112694d: rcu_exp_need_qs (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81136c97)
Location: kernel/rcu/tree_exp.h:723
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
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
In kernel/rcu/tree.c (ffffffff811322f7)
Location: kernel/rcu/tree_exp.h:723
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
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
In kernel/rcu/tree.c (ffffffff811345b8)
Location: kernel/rcu/tree_exp.h:724
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff81156c65)
Location: kernel/rcu/tree_exp.h:725
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
</details>
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
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c7e0)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffff80001018c7e0-ffff80001018c854: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03da1fc)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
c03da1fc-c03da254: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e66b0)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
c0000000001e66b0-c0000000001e670c: rcu_exp_need_qs (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffe000124bba)
Location: kernel/rcu/tree_exp.h:700
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111eef0)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff8111eef0-ffffffff8111ef2d: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110900)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff81110900-ffffffff8111093d: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_exp_need_qs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cde0)
Location: kernel/rcu/tree_exp.h:700
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff8111cde0-ffffffff8111ce1d: rcu_exp_need_qs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
</ul>

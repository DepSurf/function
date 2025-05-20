# Function: <code>rcu_rnp_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7b30)
Location: kernel/rcu/tree.c:226
Inline: False
```
**Symbols:**

```
ffffffff810e7b30-ffffffff810e7b3f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edd40)
Location: kernel/rcu/tree.c:226
Inline: False
```
**Symbols:**

```
ffffffff810edd40-ffffffff810edd4f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4e20)
Location: kernel/rcu/tree.c:227
Inline: False
```
**Symbols:**

```
ffffffff810f4e20-ffffffff810f4e2f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3b33)
Location: kernel/rcu/tree.c:212
Inline: True
```
**Symbols:**

```
ffffffff810f5b60-ffffffff810f5b6f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fcce9)
Location: kernel/rcu/tree.c:209
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff810ff960-ffffffff810ff96f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104e30)
Location: kernel/rcu/tree.c:209
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81107c90-ffffffff81107c9f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114513)
Location: kernel/rcu/tree.c:195
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff811131d0-ffffffff811131df: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e53a)
Location: kernel/rcu/tree.c:190
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8111cd70-ffffffff8111cd7f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112aaba)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81129250-ffffffff8112925f: rcu_rnp_online_cpus (STB_GLOBAL)
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
In kernel/rcu/tree.c (ffffffff81139024)
Location: kernel/rcu/tree.c:202
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff8112f040)
Location: kernel/rcu/tree.c:207
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff8112f5a0)
Location: kernel/rcu/tree.c:213
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff81150d57)
Location: kernel/rcu/tree.c:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff8117e210)
Location: kernel/rcu/tree.c:220
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff811b8d67)
Location: kernel/rcu/tree.c:223
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff811cb3a7)
Location: kernel/rcu/tree.c:4088
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/tree.c (ffffffff811dd6b7)
Location: kernel/rcu/tree.c:4236
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_cpu_online
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018cd20)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffff8000101907b8-ffff8000101907e0: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dada0)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
c03de32c-c03de348: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7484)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
c0000000001ebae0-c0000000001ebaf0: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120c7c)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffe000123df2-ffffffe000123e14: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112309a)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81121830-ffffffff8112183f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81115bdc)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81113f10-ffffffff81113f1f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120f8a)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8111f720-ffffffff8111f72f: rcu_rnp_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int rcu_rnp_online_cpus(struct rcu_node *rnp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ac84)
Location: kernel/rcu/tree.c:191
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8112b850-ffffffff8112b85f: rcu_rnp_online_cpus (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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

# Function: <code>rcu_dynticks_snap</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_dynticks *rdtp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f6cf7)
Location: kernel/rcu/tree.c:372
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init_one
```
**Symbols:**

```
ffffffff810f5c20-ffffffff810f5c35: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_dynticks *rdtp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81100d37)
Location: kernel/rcu/tree.c:369
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff810ffa20-ffffffff810ffa35: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_dynticks *rdtp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104acf)
Location: kernel/rcu/tree.c:356
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81107d30-ffffffff81107d45: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114292)
Location: kernel/rcu/tree.c:312
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81113250-ffffffff81113268: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a933)
Location: kernel/rcu/tree.c:307
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8111ce20-ffffffff8111ce38: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126d4f)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81129300-ffffffff81129318: rcu_dynticks_snap (STB_GLOBAL)
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
In kernel/rcu/tree.c (ffffffff811349ee)
Location: kernel/rcu/tree.c:323
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_boot_init_percpu_data
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
In kernel/rcu/tree.c (ffffffff8113048e)
Location: kernel/rcu/tree.c:328
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_boot_init_percpu_data
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
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
In kernel/rcu/tree.c (ffffffff81130a4d)
Location: kernel/rcu/tree.c:334
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
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
In kernel/rcu/tree.c (ffffffff81152659)
Location: kernel/rcu/tree.c:337
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
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
In kernel/rcu/tree.c (ffffffff8117aa79)
Location: kernel/rcu/tree.c:348
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
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
In kernel/rcu/tree.c (ffffffff811b57a5)
Location: kernel/rcu/tree.c:289
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff811c6735)
Location: kernel/rcu/tree.c:270
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff811d6995)
Location: kernel/rcu/tree.c:271
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
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
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f6b0)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffff8000101908a0-ffff8000101908f8: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03daf00)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
c03de428-c03de468: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7670)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
c0000000001ebbe0-c0000000001ebc14: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000121980)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffe000123e7e-ffffffe000123eae: rcu_dynticks_snap (STB_GLOBAL)
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
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f32f)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff811218e0-ffffffff811218f8: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110d9f)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff81113fc0-ffffffff81113fd8: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d21f)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8111f7d0-ffffffff8111f7e8: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rcu_dynticks_snap(struct rcu_data *rdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811280ef)
Location: kernel/rcu/tree.c:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8112b920-ffffffff8112b938: rcu_dynticks_snap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rcu_data *rdp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rcu_dynticks *rdtp</code>
</li>
</ul>
</details>
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

# Function: <code>srcu_gp_start_if_needed</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e640)
Location: kernel/rcu/srcutree.c:816
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8112e640-ffffffff8112e7a3: srcu_gp_start_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fb20)
Location: kernel/rcu/srcutree.c:808
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8114fb20-ffffffff8114fc81: srcu_gp_start_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81176e10)
Location: kernel/rcu/srcutree.c:1080
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff81176e10-ffffffff81176fbc: srcu_gp_start_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae370)
Location: kernel/rcu/srcutree.c:1144
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff811ae370-ffffffff811ae547: srcu_gp_start_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c0360)
Location: kernel/rcu/srcutree.c:1218
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff811c0360-ffffffff811c052c: srcu_gp_start_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int srcu_gp_start_if_needed(struct srcu_struct *ssp, struct callback_head *rhp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0800)
Location: kernel/rcu/srcutree.c:1209
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:start_poll_synchronize_srcu
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff811d0800-ffffffff811d0a01: srcu_gp_start_if_needed (STB_LOCAL)
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

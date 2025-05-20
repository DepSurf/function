# Function: <code>rcu_start_this_gp</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110618a)
Location: kernel/rcu/tree.c:1644
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1471
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1123
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135990)
Location: kernel/rcu/tree.c:1330
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81135990-ffffffff81135ae2: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131140)
Location: kernel/rcu/tree.c:1410
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81131140-ffffffff81131292: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131890)
Location: kernel/rcu/tree.c:1414
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81131890-ffffffff811319e2: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811538b0)
Location: kernel/rcu/tree.c:1367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811538b0-ffffffff81153a02: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81177d60)
Location: kernel/rcu/tree.c:1383
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81177d60-ffffffff81177edf: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811af440)
Location: kernel/rcu/tree.c:958
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811af440-ffffffff811af5bf: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c14b0)
Location: kernel/rcu/tree.c:918
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811c14b0-ffffffff811c162f: rcu_start_this_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node *rnp_start, struct rcu_data *rdp, long unsigned int gp_seq_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d19b0)
Location: kernel/rcu/tree.c:928
Inline: False
Direct callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811d19b0-ffffffff811d1b2f: rcu_start_this_gp (STB_LOCAL)
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffe00012276c)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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

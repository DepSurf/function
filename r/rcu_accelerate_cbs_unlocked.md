# Function: <code>rcu_accelerate_cbs_unlocked</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112100)
Location: kernel/rcu/tree.c:1635
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff81112100-ffffffff81112176: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111b9e0)
Location: kernel/rcu/tree.c:1289
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8111b9e0-ffffffff8111ba58: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128150)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81128150-ffffffff811281c8: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135b70)
Location: kernel/rcu/tree.c:1498
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81135b70-ffffffff81135bea: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131400)
Location: kernel/rcu/tree.c:1579
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81131400-ffffffff8113147a: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131b10)
Location: kernel/rcu/tree.c:1587
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81131b10-ffffffff81131b8a: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1540
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81153b30-ffffffff81153bc2: rcu_accelerate_cbs_unlocked (STB_LOCAL)
ffffffff81caefca-ffffffff81caefdf: rcu_accelerate_cbs_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811793d0-ffffffff8117947e: rcu_accelerate_cbs_unlocked (STB_LOCAL)
ffffffff81e5f21e-ffffffff81e5f233: rcu_accelerate_cbs_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1131
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811b0b60-ffffffff811b0c0e: rcu_accelerate_cbs_unlocked (STB_LOCAL)
ffffffff82059f64-ffffffff82059f79: rcu_accelerate_cbs_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1091
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811c2b30-ffffffff811c2bde: rcu_accelerate_cbs_unlocked (STB_LOCAL)
ffffffff820d876a-ffffffff820d877f: rcu_accelerate_cbs_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1133
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rdp
```
**Symbols:**

```
ffffffff811d4b00-ffffffff811d4bb5: rcu_accelerate_cbs_unlocked (STB_LOCAL)
ffffffff821b3ad3-ffffffff821b3ae8: rcu_accelerate_cbs_unlocked.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018cfe8)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffff80001018cfe8-ffff80001018d0c0: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dbb20)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c03dbb20-c03dbbb8: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e8c20)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c0000000001e8c20-c0000000001e8d40: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000122a62)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffe000122a62-ffffffe000122b2a: rcu_accelerate_cbs_unlocked (STB_LOCAL)
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
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120730)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81120730-ffffffff811207a8: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112a50)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81112a50-ffffffff81112adc: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e620)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8111e620-ffffffff8111e698: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_accelerate_cbs_unlocked(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811295a0)
Location: kernel/rcu/tree.c:1298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811295a0-ffffffff8112961b: rcu_accelerate_cbs_unlocked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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

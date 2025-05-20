# Function: <code>rcu_do_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7263)
Location: kernel/rcu/tree.c:2654
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ed4cc)
Location: kernel/rcu/tree.c:2737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f444c)
Location: kernel/rcu/tree.c:2741
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f534b)
Location: kernel/rcu/tree.c:2741
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff810ff11b)
Location: kernel/rcu/tree.c:2722
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff81106b64)
Location: kernel/rcu/tree.c:2522
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff81112e7f)
Location: kernel/rcu/tree.c:2424
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
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
In kernel/rcu/tree.c (ffffffff8111c719)
Location: kernel/rcu/tree.c:2077
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127b10)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81127b10-ffffffff81127db1: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136310)
Location: kernel/rcu/tree.c:2361
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81136310-ffffffff811365b1: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131b40)
Location: kernel/rcu/tree.c:2481
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81131b40-ffffffff81131e21: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132ad0)
Location: kernel/rcu/tree.c:2494
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81132ad0-ffffffff81132e90: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2445
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81154d00-ffffffff81155103: rcu_do_batch (STB_LOCAL)
ffffffff81caf46b-ffffffff81caf486: rcu_do_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2516
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8117c100-ffffffff8117c52e: rcu_do_batch (STB_LOCAL)
ffffffff81e5fb7a-ffffffff81e5fb95: rcu_do_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b38d0)
Location: kernel/rcu/tree.c:2184
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811b38d0-ffffffff811b3d4d: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c56a0)
Location: kernel/rcu/tree.c:2065
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811c56a0-ffffffff811c5b30: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2119
Inline: False
Direct callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811ddde0-ffffffff811de376: rcu_do_batch (STB_LOCAL)
ffffffff821b3f8d-ffffffff821b3fb7: rcu_do_batch.cold (STB_LOCAL)
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
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f1b0)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffff80001018f1b0-ffff80001018f474: rcu_do_batch (STB_LOCAL)
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
In kernel/rcu/tree.c (c03ddb1c)
Location: kernel/rcu/tree.c:2112
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (c0000000001eb220)
Location: kernel/rcu/tree.c:2112
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
In kernel/rcu/tree.c (ffffffe000122c3a)
Location: kernel/rcu/tree.c:2112
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
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
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811200f0)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff811200f0-ffffffff81120391: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110260)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff81110260-ffffffff81110662: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111dfe0)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8111dfe0-ffffffff8111e281: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_do_batch(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112b040)
Location: kernel/rcu/tree.c:2112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8112b040-ffffffff8112b2e1: rcu_do_batch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

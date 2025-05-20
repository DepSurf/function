# Function: <code>__call_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7810)
Location: kernel/rcu/tree.c:3040
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff810e7810-ffffffff810e7acf: __call_rcu.constprop.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eda40)
Location: kernel/rcu/tree.c:3118
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff810eda40-ffffffff810edcd4: __call_rcu.constprop.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f49b0)
Location: kernel/rcu/tree.c:3121
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff810f49b0-ffffffff810f4c44: __call_rcu.constprop.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f57a0)
Location: kernel/rcu/tree.c:3110
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff810f57a0-ffffffff810f598d: __call_rcu.constprop.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff580)
Location: kernel/rcu/tree.c:3091
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff810ff580-ffffffff810ff78e: __call_rcu.constprop.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811064a0)
Location: kernel/rcu/tree.c:2897
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu_bh
  - kernel/rcu/tree.c:call_rcu_sched
```
**Symbols:**

```
ffffffff811064a0-ffffffff811066b5: __call_rcu.constprop.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112180)
Location: kernel/rcu/tree.c:2853
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81112180-ffffffff81112352: __call_rcu.constprop.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ba60)
Location: kernel/rcu/tree.c:2492
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff8111ba60-ffffffff8111bc2e: __call_rcu.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811281d0)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff811281d0-ffffffff8112839d: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811369d0)
Location: kernel/rcu/tree.c:2856
Inline: False
Direct callers:
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff811369d0-ffffffff81136c17: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132030)
Location: kernel/rcu/tree.c:2993
Inline: False
Direct callers:
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81132030-ffffffff81132277: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132860)
Location: kernel/rcu/tree.c:3011
Inline: False
Direct callers:
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81132860-ffffffff81132ab8: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154a90)
Location: kernel/rcu/tree.c:2962
Inline: False
Direct callers:
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81154a90-ffffffff81154cef: __call_rcu (STB_LOCAL)
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
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018ef60)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffff80001018ef60-ffff80001018f13c: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc3b0)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
c03dc3b0-c03dc5f0: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9870)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
c0000000001e9870-c0000000001e9a90: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001231a2)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffe0001231a2-ffffffe000123332: __call_rcu (STB_LOCAL)
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
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811207b0)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff811207b0-ffffffff8112097d: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113970)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81113970-ffffffff81113e77: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e6a0)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff8111e6a0-ffffffff8111e86d: __call_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __call_rcu(struct callback_head *head, rcu_callback_t func, bool lazy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a990)
Location: kernel/rcu/tree.c:2556
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff8112a990-ffffffff8112ab9c: __call_rcu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool lazy</code>
</li>
</ul>
</details>
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

# Function: <code>__call_srcu</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1de0)
Location: kernel/rcu/srcutree.c:813
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff810f1de0-ffffffff810f2133: __call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbb50)
Location: kernel/rcu/srcutree.c:814
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff810fbb50-ffffffff810fbea6: __call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81104040)
Location: kernel/rcu/srcutree.c:844
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff81104040-ffffffff81104385: __call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fa00)
Location: kernel/rcu/srcutree.c:859
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8110fa00-ffffffff8110fdc1: __call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811188d0)
Location: kernel/rcu/srcutree.c:834
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff811188d0-ffffffff81118c81: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124ca0)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff81124ca0-ffffffff81125051: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132900)
Location: kernel/rcu/srcutree.c:848
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff81132900-ffffffff81132a78: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e0f0)
Location: kernel/rcu/srcutree.c:838
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8112e0f0-ffffffff8112e25a: __call_srcu (STB_LOCAL)
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
In kernel/rcu/srcutree.c (ffffffff8112e7b5)
Location: kernel/rcu/srcutree.c:881
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:call_srcu
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
In kernel/rcu/srcutree.c (ffffffff8114fcb5)
Location: kernel/rcu/srcutree.c:873
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:call_srcu
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
In kernel/rcu/srcutree.c (ffffffff81177090)
Location: kernel/rcu/srcutree.c:1158
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
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
In kernel/rcu/srcutree.c (ffffffff811ae650)
Location: kernel/rcu/srcutree.c:1227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
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
In kernel/rcu/srcutree.c (ffffffff811c0630)
Location: kernel/rcu/srcutree.c:1301
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
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
In kernel/rcu/srcutree.c (ffffffff811d0b10)
Location: kernel/rcu/srcutree.c:1321
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:call_srcu
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
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b1e8)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffff80001018b1e8-ffff80001018b658: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9010)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
c03d9010-c03d9414: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e4c20)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
c0000000001e4c20-c0000000001e50d0: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f5d8)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffe00011f5d8-ffffffe00011f93c: __call_srcu (STB_LOCAL)
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
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d280)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8111d280-ffffffff8111d631: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e340)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8110e340-ffffffff8110e6e7: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b170)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff8111b170-ffffffff8111b521: __call_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81127140)
Location: kernel/rcu/srcutree.c:835
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:call_srcu
```
**Symbols:**

```
ffffffff81127140-ffffffff811274f1: __call_srcu (STB_LOCAL)
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
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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

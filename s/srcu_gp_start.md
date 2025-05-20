# Function: <code>srcu_gp_start</code>

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
void srcu_gp_start(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f14c0)
Location: kernel/rcu/srcutree.c:409
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810f14c0-ffffffff810f1571: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb220)
Location: kernel/rcu/srcutree.c:410
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810fb220-ffffffff810fb2da: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811036b0)
Location: kernel/rcu/srcutree.c:441
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff811036b0-ffffffff8110375a: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f040)
Location: kernel/rcu/srcutree.c:447
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110f040-ffffffff8110f10c: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811187f0)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff811187f0-ffffffff811188ce: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124bc0)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81124bc0-ffffffff81124c9e: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811325c0)
Location: kernel/rcu/srcutree.c:451
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff811325c0-ffffffff8113267a: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112ddb0)
Location: kernel/rcu/srcutree.c:440
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8112ddb0-ffffffff8112de6a: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e300)
Location: kernel/rcu/srcutree.c:443
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8112e300-ffffffff8112e3ba: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f7d0)
Location: kernel/rcu/srcutree.c:435
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8114f7d0-ffffffff8114f88a: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81176910)
Location: kernel/rcu/srcutree.c:660
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff81176910-ffffffff81176a23: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811accc0)
Location: kernel/rcu/srcutree.c:723
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
**Symbols:**

```
ffffffff811accc0-ffffffff811acdf5: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811bebf0)
Location: kernel/rcu/srcutree.c:771
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff811bebf0-ffffffff811bed37: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cf110)
Location: kernel/rcu/srcutree.c:773
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff811cf110-ffffffff811cf1a9: srcu_gp_start (STB_LOCAL)
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
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018a1a8)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffff80001018a1a8-ffff80001018a2d4: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8de8)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
c03d8de8-c03d8f38: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e4ad0)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c0000000001e4ad0-c0000000001e4c20: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f410)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffe00011f410-ffffffe00011f50c: srcu_gp_start (STB_LOCAL)
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
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d1a0)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111d1a0-ffffffff8111d27e: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e260)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110e260-ffffffff8110e33e: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b090)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111b090-ffffffff8111b16e: srcu_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcu_gp_start(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126b40)
Location: kernel/rcu/srcutree.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81126b40-ffffffff81126c1c: srcu_gp_start (STB_LOCAL)
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

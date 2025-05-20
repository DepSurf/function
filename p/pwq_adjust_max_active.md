# Function: <code>pwq_adjust_max_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810999a0)
Location: kernel/workqueue.c:3315
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:link_pwq
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810999a0-ffffffff81099a61: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109cf30)
Location: kernel/workqueue.c:3416
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff8109cf30-ffffffff8109cffd: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a01e0)
Location: kernel/workqueue.c:3442
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810a01e0-ffffffff810a02b1: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109df60)
Location: kernel/workqueue.c:3440
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff8109df60-ffffffff8109e031: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a46e0)
Location: kernel/workqueue.c:3451
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810a46e0-ffffffff810a47b1: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aaca0)
Location: kernel/workqueue.c:3524
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810aaca0-ffffffff810aad71: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b3d20)
Location: kernel/workqueue.c:3547
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810b3d20-ffffffff810b3df1: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9c30)
Location: kernel/workqueue.c:3688
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810b9c30-ffffffff810b9cf8: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c00b0)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810c00b0-ffffffff810c0178: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c77c0)
Location: kernel/workqueue.c:3706
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff810c77c0-ffffffff810c7888: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2790)
Location: kernel/workqueue.c:3712
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff810c2790-ffffffff810c286a: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4490)
Location: kernel/workqueue.c:3719
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff810c4490-ffffffff810c456a: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3758
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff810d70a0-ffffffff810d718e: pwq_adjust_max_active (STB_LOCAL)
ffffffff81ca5105-ffffffff81ca511a: pwq_adjust_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3741
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff810f0d30-ffffffff810f0e2a: pwq_adjust_max_active (STB_LOCAL)
ffffffff81e549e9-ffffffff81e549fe: pwq_adjust_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3748
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff81112990-ffffffff81112a8a: pwq_adjust_max_active (STB_LOCAL)
ffffffff8205653b-ffffffff82056550: pwq_adjust_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4076
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff8111f680-ffffffff8111f77a: pwq_adjust_max_active (STB_LOCAL)
ffffffff820d4af4-ffffffff820d4b09: pwq_adjust_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4153
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
**Symbols:**

```
ffffffff811287d0-ffffffff81128897: pwq_adjust_max_active (STB_LOCAL)
ffffffff821af96f-ffffffff821af984: pwq_adjust_max_active.cold (STB_LOCAL)
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
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011dd10)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffff80001011dd10-ffff80001011de5c: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c037189c)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
c037189c-c037198c: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000166020)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
c000000000166020-c000000000166150: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6ce6)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffe0000d6ce6-ffffffe0000d6da0: pwq_adjust_max_active (STB_LOCAL)
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
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ba420)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810ba420-ffffffff810ba4e8: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8d60)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810a8d60-ffffffff810a8e28: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9980)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810b9980-ffffffff810b9a48: pwq_adjust_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pwq_adjust_max_active(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2ac0)
Location: kernel/workqueue.c:3697
Inline: False
Direct callers:
  - kernel/workqueue.c:thaw_workqueues
  - kernel/workqueue.c:freeze_workqueues_begin
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
**Symbols:**

```
ffffffff810c2ac0-ffffffff810c2b88: pwq_adjust_max_active (STB_LOCAL)
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

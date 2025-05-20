# Function: <code>call_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e3aa0)
Location: kernel/rcu/srcu.c:387
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
```
**Symbols:**

```
ffffffff810e3aa0-ffffffff810e3b10: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e9db0)
Location: kernel/rcu/srcu.c:387
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
```
**Symbols:**

```
ffffffff810e9db0-ffffffff810e9e20: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0c80)
Location: kernel/rcu/srcu.c:387
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff810f0c80-ffffffff810f0cf0: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f2140)
Location: kernel/rcu/srcutree.c:870
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff810f2140-ffffffff810f2155: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbeb0)
Location: kernel/rcu/srcutree.c:871
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff810fbeb0-ffffffff810fbec5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *sp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81104390)
Location: kernel/rcu/srcutree.c:901
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81104390-ffffffff811043a5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fdd0)
Location: kernel/rcu/srcutree.c:919
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8110fdd0-ffffffff8110fde5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118c90)
Location: kernel/rcu/srcutree.c:894
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_call_srcu
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81118c90-ffffffff81118ca5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125060)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81125060-ffffffff81125075: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132a80)
Location: kernel/rcu/srcutree.c:908
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81132a80-ffffffff81132a95: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e260)
Location: kernel/rcu/srcutree.c:897
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:devlink_dev_release
```
**Symbols:**

```
ffffffff8112e260-ffffffff8112e275: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e7b0)
Location: kernel/rcu/srcutree.c:911
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff8112e7b0-ffffffff8112e7c9: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fcb0)
Location: kernel/rcu/srcutree.c:903
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff8114fcb0-ffffffff8114fcc9: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81176ff0)
Location: kernel/rcu/srcutree.c:1188
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff81176ff0-ffffffff81177015: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae5a0)
Location: kernel/rcu/srcutree.c:1257
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff811ae5a0-ffffffff811ae5c5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c0580)
Location: kernel/rcu/srcutree.c:1331
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff811c0580-ffffffff811c05a5: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0a60)
Location: kernel/rcu/srcutree.c:1351
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
```
**Symbols:**

```
ffffffff811d0a60-ffffffff811d0a85: call_srcu (STB_GLOBAL)
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
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b658)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffff80001018b658-ffff80001018b6a0: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9414)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
c03d9414-c03d9434: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e50d0)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
c0000000001e50d0-c0000000001e50e8: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f93c)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffe00011f93c-ffffffe00011f978: call_srcu (STB_GLOBAL)
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
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d640)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8111d640-ffffffff8111d655: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e6f0)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8110e6f0-ffffffff8110e705: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b530)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8111b530-ffffffff8111b545: call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct *ssp, struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81127500)
Location: kernel/rcu/srcutree.c:895
Inline: False
Direct callers:
  - kernel/tracepoint.c:rcu_free_old_probes
  - mm/mmu_notifier.c:mmu_notifier_put
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81127500-ffffffff81127515: call_srcu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct callback_head *rhp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct callback_head *head</code>
</li>
</ul>
</details>
</li>
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

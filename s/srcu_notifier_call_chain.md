# Function: <code>srcu_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a17f0)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/clk/clk.c:__clk_notify
```
**Symbols:**

```
ffffffff810a17f0-ffffffff810a1808: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4f10)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff810a4f10-ffffffff810a4f28: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aab70)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff810aab70-ffffffff810aab88: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7670)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff810a7670-ffffffff810a7688: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810addf0)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff810addf0-ffffffff810ade08: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4c60)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff810b4c60-ffffffff810b4c78: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bddb0)
Location: kernel/notifier.c:504
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810bddb0-ffffffff810bddc8: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3f20)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810c3f20-ffffffff810c3f38: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cd030)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810cd030-ffffffff810cd048: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6910)
Location: kernel/notifier.c:471
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810d6910-ffffffff810d6928: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d19a0)
Location: kernel/notifier.c:497
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810d19a0-ffffffff810d1a3b: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3580)
Location: kernel/notifier.c:497
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810d3580-ffffffff810d361b: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6710)
Location: kernel/notifier.c:478
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810e6710-ffffffff810e67ab: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811007c0)
Location: kernel/notifier.c:542
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff811007c0-ffffffff81100867: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125710)
Location: kernel/notifier.c:542
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff81125710-ffffffff811257b7: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132a20)
Location: kernel/notifier.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff81132a20-ffffffff81132a9a: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d930)
Location: kernel/notifier.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_notify
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff8113d930-ffffffff8113d9aa: srcu_notifier_call_chain (STB_GLOBAL)
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
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012be88)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffff80001012be88-ffff80001012bed4: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c398)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
c037c398-c037c3c8: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174c60)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
c000000000174c60-c000000000174c7c: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0b58)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffe0000e0b58-ffffffe0000e0b96: srcu_notifier_call_chain (STB_GLOBAL)
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
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c73b0)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810c73b0-ffffffff810c73c8: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5bd0)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810b5bd0-ffffffff810b5be8: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6900)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810c6900-ffffffff810c6918: srcu_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int srcu_notifier_call_chain(struct srcu_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cedc0)
Location: kernel/notifier.c:506
Inline: False
Direct callers:
  - fs/locks.c:vfs_setlease
  - drivers/clk/clk.c:__clk_notify
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
**Symbols:**

```
ffffffff810cedc0-ffffffff810cedd8: srcu_notifier_call_chain (STB_GLOBAL)
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

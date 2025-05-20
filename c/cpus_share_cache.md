# Function: <code>cpus_share_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abae9)
Location: kernel/sched/core.c:1883
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff810ac790-ffffffff810ac7c1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae75c)
Location: kernel/sched/core.c:1865
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff810af0b0-ffffffff810af0e1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4897)
Location: kernel/sched/core.c:1875
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - block/blk-softirq.c:__blk_complete_request
```
**Symbols:**

```
ffffffff810b51f0-ffffffff810b5221: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0912)
Location: kernel/sched/core.c:1826
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:__blk_mq_complete_request
```
**Symbols:**

```
ffffffff810b1470-ffffffff810b14a1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7d58)
Location: kernel/sched/core.c:1845
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:__blk_mq_complete_request
```
**Symbols:**

```
ffffffff810b88a0-ffffffff810b88d1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf8bc)
Location: kernel/sched/core.c:1841
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810c03a0-ffffffff810c03d1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8bc1)
Location: kernel/sched/core.c:1839
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810c9710-ffffffff810c9741: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d059e)
Location: kernel/sched/core.c:2269
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810d1340-ffffffff810d1371: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da54e)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810db2f0-ffffffff810db321: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd516)
Location: kernel/sched/core.c:2441
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_force_complete_rq
```
**Symbols:**

```
ffffffff810e4060-ffffffff810e4091: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db6d1)
Location: kernel/sched/core.c:3120
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810e1aa0-ffffffff810e1ad1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbbe0)
Location: kernel/sched/core.c:3141
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810e38b0-ffffffff810e38e1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810efdac)
Location: kernel/sched/core.c:3708
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810fa490-ffffffff810fa511: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110cff2)
Location: kernel/sched/core.c:3803
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff81116a20-ffffffff81116aa9: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81133a92)
Location: kernel/sched/core.c:3867
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff8113df60-ffffffff8113dfe9: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811424b2)
Location: kernel/sched/core.c:3948
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff8114aa80-ffffffff8114ab09: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114d872)
Location: kernel/sched/core.c:3958
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:wake_affine
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff811565e0-ffffffff81156669: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a02c)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffff80001013afa8-ffff80001013aff8: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0389b88)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
c038a974-c038a9b8: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018770c)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
c000000000188bf0-c000000000188c38: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e98ee)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffe0000ea64c-ffffffe0000ea69e: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d49fe)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810d57a0-ffffffff810d57d1: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c304e)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810c3df0-ffffffff810c3e21: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d183e)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810d25e0-ffffffff810d2611: cpus_share_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cpus_share_cache(int this_cpu, int that_cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc202)
Location: kernel/sched/core.c:2389
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff810dd090-ffffffff810dd0c1: cpus_share_cache (STB_GLOBAL)
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

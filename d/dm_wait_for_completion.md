# Function: <code>dm_wait_for_completion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, int interruptible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1440)
Location: drivers/md/dm.c:2934
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff816a1440-ffffffff816a1580: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, int interruptible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817024f0)
Location: drivers/md/dm.c:1937
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff817024f0-ffffffff81702630: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817343e0)
Location: drivers/md/dm.c:1997
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff817343e0-ffffffff817344e7: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d7e0)
Location: drivers/md/dm.c:2207
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8174d7e0-ffffffff8174d8af: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf8d0)
Location: drivers/md/dm.c:2181
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff817bf8d0-ffffffff817bf9a9: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807950)
Location: drivers/md/dm.c:2370
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81807950-ffffffff81807a28: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833dc0)
Location: drivers/md/dm.c:2396
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81833dc0-ffffffff81833efb: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875bd0)
Location: drivers/md/dm.c:2427
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81875bd0-ffffffff81875d29: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a79d0)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818a79d0-ffffffff818a7b29: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977870)
Location: drivers/md/dm.c:2473
Inline: True
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81977870-ffffffff819778e4: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197c500)
Location: drivers/md/dm.c:2339
Inline: True
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8197c500-ffffffff8197c585: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960060)
Location: drivers/md/dm.c:2358
Inline: True
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81960060-ffffffff819601f6: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, unsigned int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a08030)
Location: drivers/md/dm.c:2247
Inline: True
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81a08030-ffffffff81a08256: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, unsigned int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b70c40)
Location: drivers/md/dm.c:2428
Inline: True
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81b70c40-ffffffff81b70df4: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, unsigned int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d9f0)
Location: drivers/md/dm.c:2530
Inline: True
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81d0d9f0-ffffffff81d0da86: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, unsigned int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d76fe0)
Location: drivers/md/dm.c:2566
Inline: True
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81d76fe0-ffffffff81d77084: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, unsigned int task_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2e210)
Location: drivers/md/dm.c:2574
Inline: True
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81e2e210-ffffffff81e2e2b4: dm_wait_for_completion (STB_LOCAL)
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
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc7d8)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffff800010afc7d8-ffff800010afc94c: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd170)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c0bdd170-c0bdd2dc: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebaf0)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c000000000bebaf0-c000000000bebcec: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006edbac)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffe0006edbac-ffffffe0006edcd2: dm_wait_for_completion (STB_LOCAL)
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
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184d850)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8184d850-ffffffff8184d9a9: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814e70)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81814e70-ffffffff81814fc9: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189ce80)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8189ce80-ffffffff8189cfd9: dm_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_wait_for_completion(struct mapped_device *md, long int task_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b91e0)
Location: drivers/md/dm.c:2432
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff818b91e0-ffffffff818b9339: dm_wait_for_completion (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int task_state</code>
</li>
<li>
<b>Param removed. </b>
<code>int interruptible</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int task_state</code> ➡️ <code>unsigned int task_state</code>
</li>
</ul>
</details>
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

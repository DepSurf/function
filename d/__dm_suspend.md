# Function: <code>__dm_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, int interruptible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a20d0)
Location: drivers/md/dm.c:3081
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff816a20d0-ffffffff816a22b8: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, int interruptible, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702d30)
Location: drivers/md/dm.c:2084
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81702d30-ffffffff81702eeb: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734c00)
Location: drivers/md/dm.c:2143
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81734c00-ffffffff81734dbb: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174dfc0)
Location: drivers/md/dm.c:2351
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff8174dfc0-ffffffff8174e1a5: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c0030)
Location: drivers/md/dm.c:2326
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff817c0030-ffffffff817c0205: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807ea0)
Location: drivers/md/dm.c:2515
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81807ea0-ffffffff81808086: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833f00)
Location: drivers/md/dm.c:2541
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81833f00-ffffffff818340c4: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2572
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81875d30-ffffffff81875ef2: __dm_suspend (STB_LOCAL)
ffffffff81879563-ffffffff81879576: __dm_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7b30)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff818a7b30-ffffffff818a7cf9: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819783a0)
Location: drivers/md/dm.c:2617
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff819783a0-ffffffff8197859d: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197dbc0)
Location: drivers/md/dm.c:2465
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff8197dbc0-ffffffff8197dd76: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960300)
Location: drivers/md/dm.c:2484
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81960300-ffffffff819604b6: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, unsigned int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a08a60)
Location: drivers/md/dm.c:2373
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81a08a60-ffffffff81a08c13: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, unsigned int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b71cc0)
Location: drivers/md/dm.c:2554
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81b71cc0-ffffffff81b71eb9: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, unsigned int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0daa0)
Location: drivers/md/dm.c:2657
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81d0daa0-ffffffff81d0dc61: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, unsigned int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d770a0)
Location: drivers/md/dm.c:2693
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81d770a0-ffffffff81d77261: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, unsigned int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2e2d0)
Location: drivers/md/dm.c:2701
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81e2e2d0-ffffffff81e2e491: __dm_suspend (STB_LOCAL)
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
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afe230)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffff800010afe230-ffff800010afe45c: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd510)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
c0bdd510-c0bdd6e4: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bec030)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
c000000000bec030-c000000000bec324: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006edee0)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffe0006edee0-ffffffe0006ee090: __dm_suspend (STB_LOCAL)
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
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184d9b0)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff8184d9b0-ffffffff8184db79: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814fd0)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81814fd0-ffffffff81815199: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189cfe0)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff8189cfe0-ffffffff8189d1a9: __dm_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __dm_suspend(struct mapped_device *md, struct dm_table *map, unsigned int suspend_flags, long int task_state, int dmf_suspended_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b9340)
Location: drivers/md/dm.c:2577
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff818b9340-ffffffff818b9509: __dm_suspend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int dmf_suspended_flag</code>
</li>
</ul>
</details>
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

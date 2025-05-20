# Function: <code>any_leases_conflict</code>

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
In fs/locks.c (ffffffff81260380)
Location: fs/locks.c:1363
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81260380-ffffffff812603cb: any_leases_conflict.isra.20 (STB_LOCAL)
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
In fs/locks.c (ffffffff8128c550)
Location: fs/locks.c:1391
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8128c550-ffffffff8128c5a5: any_leases_conflict.isra.24 (STB_LOCAL)
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
In fs/locks.c (ffffffff812a1300)
Location: fs/locks.c:1415
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812a1300-ffffffff812a1355: any_leases_conflict.isra.30 (STB_LOCAL)
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
In fs/locks.c (ffffffff812b0260)
Location: fs/locks.c:1415
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812b0260-ffffffff812b02b5: any_leases_conflict.isra.36 (STB_LOCAL)
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
In fs/locks.c (ffffffff812d3800)
Location: fs/locks.c:1425
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812d3800-ffffffff812d3855: any_leases_conflict.isra.36 (STB_LOCAL)
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
In fs/locks.c (ffffffff812fdca0)
Location: fs/locks.c:1425
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812fdca0-ffffffff812fdcf5: any_leases_conflict.isra.37 (STB_LOCAL)
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
In fs/locks.c (ffffffff81313610)
Location: fs/locks.c:1544
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81313610-ffffffff8131365b: any_leases_conflict.isra.30 (STB_LOCAL)
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
In fs/locks.c (ffffffff8133af30)
Location: fs/locks.c:1550
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8133af30-ffffffff8133af80: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81353490)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81353490-ffffffff813534e0: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139b834)
Location: fs/locks.c:1579
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ad268)
Location: fs/locks.c:1580
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff813b4468)
Location: fs/locks.c:1580
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff81404168)
Location: fs/locks.c:1483
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff814782d4)
Location: fs/locks.c:1458
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff8150abf4)
Location: fs/locks.c:1444
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff81542354)
Location: fs/locks.c:1445
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
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
In fs/locks.c (ffffffff81577874)
Location: fs/locks.c:1459
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffff800010415eb8)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffff800010415eb8-ffff800010415f34: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool any_leases_conflict(struct inode *inode, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e11e0)
Location: fs/locks.c:1576
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
c05e11e0-c05e1238: any_leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool any_leases_conflict(struct inode *inode, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000522330)
Location: fs/locks.c:1576
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
c000000000522330-c0000000005223e0: any_leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool any_leases_conflict(struct inode *inode, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc33a)
Location: fs/locks.c:1576
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffe0002bc33a-ffffffe0002bc3a2: any_leases_conflict (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134ba70)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8134ba70-ffffffff8134bac0: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133c750)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8133c750-ffffffff8133c7a0: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81349540)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81349540-ffffffff81349590: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135cbd0)
Location: fs/locks.c:1576
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8135cbd0-ffffffff8135cc20: any_leases_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

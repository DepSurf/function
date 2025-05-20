# Function: <code>leases_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260340)
Location: fs/locks.c:1353
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81260340-ffffffff81260380: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c510)
Location: fs/locks.c:1381
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8128c510-ffffffff8128c550: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a12c0)
Location: fs/locks.c:1405
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812a12c0-ffffffff812a1300: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0040)
Location: fs/locks.c:1405
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812b0040-ffffffff812b0080: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d35e0)
Location: fs/locks.c:1415
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812d35e0-ffffffff812d3620: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fdbb0)
Location: fs/locks.c:1415
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff812fdbb0-ffffffff812fdbee: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813135d0)
Location: fs/locks.c:1534
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff813135d0-ffffffff8131360e: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81339a10)
Location: fs/locks.c:1530
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81339a10-ffffffff81339ad1: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81351f60)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81351f60-ffffffff81352021: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139a4e0)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8139a4e0-ffffffff8139a5c2: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813abfc0)
Location: fs/locks.c:1557
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff813abfc0-ffffffff813ac082: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b3170)
Location: fs/locks.c:1557
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff813b3170-ffffffff813b3232: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81402e60)
Location: fs/locks.c:1460
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81402e60-ffffffff81402f1f: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477ca0)
Location: fs/locks.c:1435
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81477ca0-ffffffff81477d73: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150a560)
Location: fs/locks.c:1421
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8150a560-ffffffff8150a633: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541cf0)
Location: fs/locks.c:1422
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81541cf0-ffffffff81541db6: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81577220)
Location: fs/locks.c:1436
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81577220-ffffffff815772e6: leases_conflict (STB_LOCAL)
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
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010415dc8)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffff800010415dc8-ffff800010415eb8: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e10f0)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:any_leases_conflict
```
**Symbols:**

```
c05e10f0-c05e11e0: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000522200)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:any_leases_conflict
```
**Symbols:**

```
c000000000522200-c000000000522330: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc27c)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:any_leases_conflict
```
**Symbols:**

```
ffffffe0002bc27c-ffffffe0002bc33a: leases_conflict (STB_LOCAL)
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
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a540)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8134a540-ffffffff8134a601: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133b220)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8133b220-ffffffff8133b2e1: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81348010)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81348010-ffffffff813480d1: leases_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool leases_conflict(struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c010)
Location: fs/locks.c:1556
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8135c010-ffffffff8135c0e1: leases_conflict (STB_LOCAL)
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

# Function: <code>lease_modify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812613c0)
Location: fs/locks.c:1305
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812613c0-ffffffff8126149e: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d905)
Location: fs/locks.c:1333
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8128d550-ffffffff8128d62e: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a15b5)
Location: fs/locks.c:1357
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff812a1450-ffffffff812a152e: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0344)
Location: fs/locks.c:1357
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff812b0170-ffffffff812b025d: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d3dc4)
Location: fs/locks.c:1367
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff812d3710-ffffffff812d37fd: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff812feaca)
Location: fs/locks.c:1367
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff813016ab-ffffffff813016c8: lease_modify.cold.45 (STB_LOCAL)
ffffffff812fe990-ffffffff812fea6a: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81314280)
Location: fs/locks.c:1486
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81317197-ffffffff813171b3: lease_modify.cold.44 (STB_LOCAL)
ffffffff813140f0-ffffffff813141d4: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133bbb4)
Location: fs/locks.c:1482
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8133ea50-ffffffff8133ea6d: lease_modify.cold (STB_LOCAL)
ffffffff8133b9f0-ffffffff8133bb08: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81354104)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81357040-ffffffff8135705d: lease_modify.cold (STB_LOCAL)
ffffffff81353f40-ffffffff81354058: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8139ae24)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8139e2ee-ffffffff8139e30b: lease_modify.cold (STB_LOCAL)
ffffffff8139ac40-ffffffff8139ad72: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff813acaff)
Location: fs/locks.c:1509
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81beb9da-ffffffff81beb9f7: lease_modify.cold (STB_LOCAL)
ffffffff813ac920-ffffffff813aca52: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff813b3f8f)
Location: fs/locks.c:1509
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81bdda3c-ffffffff81bdda59: lease_modify.cold (STB_LOCAL)
ffffffff813b3db0-ffffffff813b3ee2: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81403c9c)
Location: fs/locks.c:1412
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81cc7478-ffffffff81cc7495: lease_modify.cold (STB_LOCAL)
ffffffff81403ac0-ffffffff81403bf2: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8147808f)
Location: fs/locks.c:1387
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81e799f7-ffffffff81e79a11: lease_modify.cold (STB_LOCAL)
ffffffff81477e70-ffffffff81477fe0: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150a99f)
Location: fs/locks.c:1373
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8150a750-ffffffff8150a8d3: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815420ff)
Location: fs/locks.c:1374
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81541ed0-ffffffff81542033: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157761f)
Location: fs/locks.c:1388
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81577400-ffffffff8157755f: lease_modify (STB_GLOBAL)
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
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416864)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffff800010416600-ffff800010416748: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e36e0)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
c05e2098-c05e21dc: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000525740)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
c0000000005253d0-c0000000005255b4: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bd7d8)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffe0002bd624-ffffffe0002bd736: lease_modify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134c6e4)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8134f620-ffffffff8134f63d: lease_modify.cold (STB_LOCAL)
ffffffff8134c520-ffffffff8134c638: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133d3c4)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff81340300-ffffffff8134031d: lease_modify.cold (STB_LOCAL)
ffffffff8133d200-ffffffff8133d318: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134a1b4)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8134d0f0-ffffffff8134d10d: lease_modify.cold (STB_LOCAL)
ffffffff81349ff0-ffffffff8134a108: lease_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lease_modify(struct file_lock *fl, int arg, struct list_head *dispose);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135e094)
Location: fs/locks.c:1508
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8136067b-ffffffff81360698: lease_modify.cold (STB_LOCAL)
ffffffff8135cd10-ffffffff8135ce28: lease_modify (STB_GLOBAL)
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

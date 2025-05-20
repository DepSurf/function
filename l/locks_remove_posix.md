# Function: <code>locks_remove_posix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff812615a0)
Location: fs/locks.c:2395
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812615a0-ffffffff8126165a: locks_remove_posix.part.32 (STB_LOCAL)
ffffffff81261660-ffffffff8126168b: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8128f110)
Location: fs/locks.c:2426
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8128d730-ffffffff8128d84d: locks_remove_posix.part.37 (STB_LOCAL)
ffffffff8128d850-ffffffff8128d87e: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2ca0)
Location: fs/locks.c:2464
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812a2ca0-ffffffff812a2de0: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1e80)
Location: fs/locks.c:2427
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812b1e80-ffffffff812b1fc2: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d59e0)
Location: fs/locks.c:2467
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812d59e0-ffffffff812d5b28: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300490)
Location: fs/locks.c:2472
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81300490-ffffffff813005d6: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81315f30)
Location: fs/locks.c:2584
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81315f30-ffffffff81316087: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d710)
Location: fs/locks.c:2602
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8133d710-ffffffff8133d869: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355cc0)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81355cc0-ffffffff81355e19: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d480)
Location: fs/locks.c:2695
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8139d480-ffffffff8139d65f: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aee50)
Location: fs/locks.c:2698
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff813aee50-ffffffff813af01d: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b61b0)
Location: fs/locks.c:2700
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff813b61b0-ffffffff813b637d: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405eb0)
Location: fs/locks.c:2586
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81405eb0-ffffffff8140607a: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814796f0)
Location: fs/locks.c:2572
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff814796f0-ffffffff81479885: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c080)
Location: fs/locks.c:2554
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8150c080-ffffffff8150c215: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815437f0)
Location: fs/locks.c:2530
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff815437f0-ffffffff8154398e: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81578cf0)
Location: fs/locks.c:2541
Inline: False
Direct callers:
  - fs/open.c:filp_flush
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81578cf0-ffffffff81578e8e: locks_remove_posix (STB_GLOBAL)
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
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104187f8)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffff8000104187f8-ffff800010418944: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e31cc)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
c05e31cc-c05e3358: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000526310)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
c000000000526310-c0000000005264c8: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf276)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffe0002bf276-ffffffe0002bf374: locks_remove_posix (STB_GLOBAL)
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
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e2a0)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8134e2a0-ffffffff8134e3f9: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ef80)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8133ef80-ffffffff8133f0d9: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134bd70)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8134bd70-ffffffff8134bec9: locks_remove_posix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void locks_remove_posix(struct file *filp, fl_owner_t owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135dbc0)
Location: fs/locks.c:2692
Inline: False
Direct callers:
  - fs/open.c:filp_close
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8135dbc0-ffffffff8135dd2e: locks_remove_posix (STB_GLOBAL)
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

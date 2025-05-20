# Function: <code>locks_delete_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125f0c0)
Location: fs/locks.c:618
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff8125f0c0-ffffffff8125f135: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128ab00)
Location: fs/locks.c:645
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8128ab00-ffffffff8128ab75: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8129f7e0)
Location: fs/locks.c:665
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8129f7e0-ffffffff8129f855: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ae650)
Location: fs/locks.c:665
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812ae650-ffffffff812ae6c5: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d20f0)
Location: fs/locks.c:682
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812d20f0-ffffffff812d2165: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fe5a0)
Location: fs/locks.c:682
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812fe5a0-ffffffff812fe615: locks_delete_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314300)
Location: fs/locks.c:755
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff81314300-ffffffff813143b2: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133bc40)
Location: fs/locks.c:751
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8133bc40-ffffffff8133bcf2: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354190)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff81354190-ffffffff81354240: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139a760)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8139a760-ffffffff8139a814: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ac220)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff813ac220-ffffffff813ac2d4: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b38d0)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff813b38d0-ffffffff813b3984: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814035b0)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff814035b0-ffffffff81403664: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814776c0)
Location: fs/locks.c:708
Inline: False
Direct callers:
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff814776c0-ffffffff8147777c: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509f10)
Location: fs/locks.c:694
Inline: False
Direct callers:
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81509f10-ffffffff81509fcc: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541690)
Location: fs/locks.c:695
Inline: False
Direct callers:
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81541690-ffffffff8154174c: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81576b70)
Location: fs/locks.c:694
Inline: False
Direct callers:
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81576b70-ffffffff81576c2c: locks_delete_block (STB_GLOBAL)
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
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416418)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffff800010416418-ffff800010416520: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1808)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
c05e1808-c05e18e4: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523f30)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
c000000000523f30-c000000000524054: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bd854)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffe0002bd854-ffffffe0002bd92a: locks_delete_block (STB_GLOBAL)
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
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c770)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8134c770-ffffffff8134c820: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d450)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8133d450-ffffffff8133d500: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a240)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8134a240-ffffffff8134a2f0: locks_delete_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int locks_delete_block(struct file_lock *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c6e0)
Location: fs/locks.c:758
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8135c6e0-ffffffff8135c78a: locks_delete_block (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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

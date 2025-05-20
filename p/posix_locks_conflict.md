# Function: <code>posix_locks_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812601d0)
Location: fs/locks.c:731
Inline: True
Direct callers:
  - fs/locks.c:posix_test_lock
  - fs/locks.c:__posix_lock_file
```
**Symbols:**

```
ffffffff812601d0-ffffffff81260252: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c3a0)
Location: fs/locks.c:758
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8128c3a0-ffffffff8128c424: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1140)
Location: fs/locks.c:778
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff812a1140-ffffffff812a11c4: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812afed0)
Location: fs/locks.c:778
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff812afed0-ffffffff812aff4e: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d3480)
Location: fs/locks.c:790
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff812d3480-ffffffff812d34fb: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fdb20)
Location: fs/locks.c:790
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff812fdb20-ffffffff812fdba8: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313540)
Location: fs/locks.c:898
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81313540-ffffffff813135c9: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133aee0)
Location: fs/locks.c:894
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8133aee0-ffffffff8133af2c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81353440)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81353440-ffffffff8135348c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139c3e6)
Location: fs/locks.c:918
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813998d0-ffffffff8139991c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813adde6)
Location: fs/locks.c:918
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813ab3c0-ffffffff813ab40c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5325)
Location: fs/locks.c:918
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813b2c90-ffffffff813b2cdc: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405025)
Location: fs/locks.c:918
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81402980-ffffffff814029cc: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814789af)
Location: fs/locks.c:868
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff814773b0-ffffffff81477408: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150b2df)
Location: fs/locks.c:854
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81509bb0-ffffffff81509c08: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81542a3f)
Location: fs/locks.c:855
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff815411b0-ffffffff81541208: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81577f5f)
Location: fs/locks.c:854
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81576690-ffffffff815766e8: posix_locks_conflict (STB_LOCAL)
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
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414fa0)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffff800010414fa0-ffff800010415028: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1dac)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
c05e1dac-c05e1e28: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000524720)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
c000000000524720-c000000000524798: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bcba2)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffe0002bcba2-ffffffe0002bcc0a: posix_locks_conflict (STB_LOCAL)
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
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ba20)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8134ba20-ffffffff8134ba6c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c700)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8133c700-ffffffff8133c74c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813494f0)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813494f0-ffffffff8134953c: posix_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool posix_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135caa0)
Location: fs/locks.c:918
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8135caa0-ffffffff8135caec: posix_locks_conflict (STB_LOCAL)
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
<code>int</code> ➡️ <code>bool</code>
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

# Function: <code>locks_lock_inode_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81261220)
Location: fs/locks.c:1888
Inline: True
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff81261220-ffffffff812613b2: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d3b0)
Location: fs/locks.c:1914
Inline: True
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff8128d3b0-ffffffff8128d542: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2fc0)
Location: fs/locks.c:1952
Inline: True
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff812a2fc0-ffffffff812a3107: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b21a0)
Location: fs/locks.c:1952
Inline: True
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff812b21a0-ffffffff812b22e7: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5d00)
Location: fs/locks.c:1962
Inline: True
Direct callers:
  - fs/locks.c:SyS_flock
```
**Symbols:**

```
ffffffff812d5d00-ffffffff812d5e47: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813007b0)
Location: fs/locks.c:1960
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813007b0-ffffffff813008f7: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316340)
Location: fs/locks.c:2074
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81316340-ffffffff8131649f: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133db20)
Location: fs/locks.c:2092
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8133db20-ffffffff8133dc85: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813560f0)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813560f0-ffffffff81356275: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139cf20)
Location: fs/locks.c:2184
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8139cf20-ffffffff8139d09b: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ae8f0)
Location: fs/locks.c:2185
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813ae8f0-ffffffff813aea6b: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5c50)
Location: fs/locks.c:2188
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813b5c50-ffffffff813b5dcb: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405950)
Location: fs/locks.c:2091
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81405950-ffffffff81405acb: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147a5e0)
Location: fs/locks.c:2066
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff8147a5e0-ffffffff8147a7af: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150cfd0)
Location: fs/locks.c:2052
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff8150cfd0-ffffffff8150d19f: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81544780)
Location: fs/locks.c:2029
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff81544780-ffffffff8154494f: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81579c70)
Location: fs/locks.c:2036
Inline: False
Direct callers:
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff81579c70-ffffffff81579e3f: locks_lock_inode_wait (STB_GLOBAL)
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
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418c10)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__arm64_sys_flock
```
**Symbols:**

```
ffff800010418c10-ffff800010418db0: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3fd4)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c05e3fd4-c05e416c: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000527c60)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c000000000527c60-c000000000527ec8: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf5a2)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
ffffffe0002bf5a2-ffffffe0002bf70c: locks_lock_inode_wait (STB_GLOBAL)
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
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e6d0)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8134e6d0-ffffffff8134e855: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133f3b0)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8133f3b0-ffffffff8133f535: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c1a0)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8134c1a0-ffffffff8134c325: locks_lock_inode_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int locks_lock_inode_wait(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135e9b0)
Location: fs/locks.c:2181
Inline: True
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8135e9b0-ffffffff8135eb1d: locks_lock_inode_wait (STB_GLOBAL)
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

# Function: <code>posix_lock_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c9e0)
Location: fs/locks.c:964
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8128c9e0-ffffffff8128d13c: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a23a0)
Location: fs/locks.c:986
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812a23a0-ffffffff812a2b55: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b15a0)
Location: fs/locks.c:986
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812b15a0-ffffffff812b1d37: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5090)
Location: fs/locks.c:996
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812d5090-ffffffff812d588a: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ffad0)
Location: fs/locks.c:996
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812ffad0-ffffffff81300350: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813155a0)
Location: fs/locks.c:1111
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff813155a0-ffffffff81315ecb: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133cee0)
Location: fs/locks.c:1107
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8133cee0-ffffffff8133d6a8: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355490)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff81355490-ffffffff81355c58: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139c330)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8139c330-ffffffff8139ccb2: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813add30)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff813add30-ffffffff813ae684: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5270)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff813b5270-ffffffff813b5c2e: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81404f70)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_lock_inode_wait
```
**Symbols:**

```
ffffffff81404f70-ffffffff8140592b: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814788e0)
Location: fs/locks.c:1092
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_lock_inode_wait
```
**Symbols:**

```
ffffffff814788e0-ffffffff814794f2: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150b210)
Location: fs/locks.c:1078
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_lock_inode_wait
```
**Symbols:**

```
ffffffff8150b210-ffffffff8150be22: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81542970)
Location: fs/locks.c:1079
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_lock_inode_wait
```
**Symbols:**

```
ffffffff81542970-ffffffff81543582: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81577e90)
Location: fs/locks.c:1093
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_lock_inode_wait
```
**Symbols:**

```
ffffffff81577e90-ffffffff81578a88: posix_lock_inode (STB_LOCAL)
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
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010417f40)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffff800010417f40-ffff800010418738: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e2880)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
c05e2880-c05e3168: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000525880)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
c000000000525880-c000000000526278: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002beb92)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffe0002beb92-ffffffe0002bf1de: posix_lock_inode (STB_LOCAL)
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
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134da70)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8134da70-ffffffff8134e238: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e750)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8133e750-ffffffff8133ef18: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b540)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8134b540-ffffffff8134bd08: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_lock_inode(struct inode *inode, struct file_lock *request, struct file_lock *conflock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135d330)
Location: fs/locks.c:1131
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8135d330-ffffffff8135db5e: posix_lock_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>__traceiter_flock_lock_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813a9f40)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff813a9f40-ffffffff813a9f91: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b1420)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff813b1420-ffffffff813b146f: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81401110)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff81401110-ffffffff8140115f: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814752a0)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff814752a0-ffffffff814752fb: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815076d0)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff815076d0-ffffffff8150772b: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8153ed00)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff8153ed00-ffffffff8153ed5b: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_flock_lock_inode(void *__data, struct inode *inode, struct file_lock *fl, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815741e0)
Location: include/trace/events/filelock.h:115
Inline: False
```
**Symbols:**

```
ffffffff815741e0-ffffffff8157423b: __traceiter_flock_lock_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

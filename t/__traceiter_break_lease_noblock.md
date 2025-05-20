# Function: <code>__traceiter_break_lease_noblock</code>

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
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813a9fa0)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff813a9fa0-ffffffff813a9fe7: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b1470)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff813b1470-ffffffff813b14b5: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81401160)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff81401160-ffffffff814011a5: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81475300)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff81475300-ffffffff8147534f: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81507740)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff81507740-ffffffff8150778f: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8153ed70)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff8153ed70-ffffffff8153edbf: __traceiter_break_lease_noblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_break_lease_noblock(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81574250)
Location: include/trace/events/filelock.h:156
Inline: False
```
**Symbols:**

```
ffffffff81574250-ffffffff8157429f: __traceiter_break_lease_noblock (STB_GLOBAL)
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

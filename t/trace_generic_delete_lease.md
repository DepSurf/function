# Function: <code>trace_generic_delete_lease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812620e3)
Location: include/trace/events/filelock.h:84
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128df1f)
Location: include/trace/events/filelock.h:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1e18)
Location: include/trace/events/filelock.h:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0bcb)
Location: include/trace/events/filelock.h:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d466b)
Location: include/trace/events/filelock.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fec92)
Location: include/trace/events/filelock.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813146da)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c01b)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135455b)
Location: include/trace/events/filelock.h:165
Inline: True
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
In fs/locks.c (ffffffff8139af73)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
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
In fs/locks.c (ffffffff813ac7a6)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_delete_lease
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b4b81)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff813b3040-ffffffff813b307f: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81404881)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81402d30-ffffffff81402d6c: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81479e6e)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81477b10-ffffffff81477b92: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c81e)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff8150a3b0-ffffffff8150a432: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81543fb1)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81541b40-ffffffff81541bc2: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_generic_delete_lease(struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157948c)
Location: include/trace/events/filelock.h:165
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81576e50-ffffffff81576ed2: trace_generic_delete_lease (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104173cc)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e4278)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000526ee4)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bdcf0)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134cb3b)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d81b)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a60b)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135eeaf)
Location: include/trace/events/filelock.h:165
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

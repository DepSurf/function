# Function: <code>__traceiter_ext4_free_blocks</code>

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
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814318f0)
Location: include/trace/events/ext4.h:888
Inline: False
```
**Symbols:**

```
ffffffff814318f0-ffffffff8143194b: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438480)
Location: include/trace/events/ext4.h:888
Inline: False
```
**Symbols:**

```
ffffffff81438480-ffffffff814384d9: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148c100)
Location: include/trace/events/ext4.h:888
Inline: False
```
**Symbols:**

```
ffffffff8148c100-ffffffff8148c159: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81510030)
Location: include/trace/events/ext4.h:894
Inline: False
```
**Symbols:**

```
ffffffff81510030-ffffffff81510098: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ab0e0)
Location: include/trace/events/ext4.h:896
Inline: False
```
**Symbols:**

```
ffffffff815ab0e0-ffffffff815ab148: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e1a80)
Location: include/trace/events/ext4.h:903
Inline: False
```
**Symbols:**

```
ffffffff815e1a80-ffffffff815e1ae8: __traceiter_ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_free_blocks(void *__data, struct inode *inode, __u64 block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161a480)
Location: include/trace/events/ext4.h:900
Inline: False
```
**Symbols:**

```
ffffffff8161a480-ffffffff8161a4e8: __traceiter_ext4_free_blocks (STB_GLOBAL)
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

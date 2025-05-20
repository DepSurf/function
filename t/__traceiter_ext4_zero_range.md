# Function: <code>__traceiter_ext4_zero_range</code>

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
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81432010)
Location: include/trace/events/ext4.h:1461
Inline: False
```
**Symbols:**

```
ffffffff81432010-ffffffff8143206b: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438aa0)
Location: include/trace/events/ext4.h:1403
Inline: False
```
**Symbols:**

```
ffffffff81438aa0-ffffffff81438af9: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148c720)
Location: include/trace/events/ext4.h:1403
Inline: False
```
**Symbols:**

```
ffffffff8148c720-ffffffff8148c779: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81510710)
Location: include/trace/events/ext4.h:1409
Inline: False
```
**Symbols:**

```
ffffffff81510710-ffffffff81510778: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ab8f0)
Location: include/trace/events/ext4.h:1411
Inline: False
```
**Symbols:**

```
ffffffff815ab8f0-ffffffff815ab958: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e2350)
Location: include/trace/events/ext4.h:1418
Inline: False
```
**Symbols:**

```
ffffffff815e2350-ffffffff815e23b8: __traceiter_ext4_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_zero_range(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161ad50)
Location: include/trace/events/ext4.h:1415
Inline: False
```
**Symbols:**

```
ffffffff8161ad50-ffffffff8161adb8: __traceiter_ext4_zero_range (STB_GLOBAL)
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

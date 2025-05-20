# Function: <code>__traceiter_ext4_fc_track_inode</code>

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
int __traceiter_ext4_fc_track_inode(void *__data, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814336a0)
Location: include/trace/events/ext4.h:2967
Inline: False
```
**Symbols:**

```
ffffffff814336a0-ffffffff814336e7: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81439e80)
Location: include/trace/events/ext4.h:2791
Inline: False
```
**Symbols:**

```
ffffffff81439e80-ffffffff81439ec5: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148db00)
Location: include/trace/events/ext4.h:2791
Inline: False
```
**Symbols:**

```
ffffffff8148db00-ffffffff8148db45: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, handle_t *handle, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81511e20)
Location: include/trace/events/ext4.h:2826
Inline: False
```
**Symbols:**

```
ffffffff81511e20-ffffffff81511e7b: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, handle_t *handle, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ad450)
Location: include/trace/events/ext4.h:2864
Inline: False
```
**Symbols:**

```
ffffffff815ad450-ffffffff815ad4ab: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, handle_t *handle, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e4190)
Location: include/trace/events/ext4.h:2871
Inline: False
```
**Symbols:**

```
ffffffff815e4190-ffffffff815e41eb: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_fc_track_inode(void *__data, handle_t *handle, struct inode *inode, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161cb90)
Location: include/trace/events/ext4.h:2868
Inline: False
```
**Symbols:**

```
ffffffff8161cb90-ffffffff8161cbeb: __traceiter_ext4_fc_track_inode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t *handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, inode, ret</code> ➡️ <code>__data, handle, inode, ret</code>
</li>
</ul>
</details>
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

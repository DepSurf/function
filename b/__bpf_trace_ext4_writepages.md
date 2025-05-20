# Function: <code>__bpf_trace_ext4_writepages</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d250)
Location: include/trace/events/ext4.h:370
Inline: False
```
**Symbols:**

```
ffffffff8137d250-ffffffff8137d25b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813959b0)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813959b0-ffffffff813959bb: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bf830)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813bf830-ffffffff813bf83b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8b00)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813d8b00-ffffffff813d8b0b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425230)
Location: include/trace/events/ext4.h:411
Inline: True
```
**Symbols:**

```
ffffffff81425230-ffffffff8142523b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cbd0)
Location: include/trace/events/ext4.h:422
Inline: True
```
**Symbols:**

```
ffffffff8143cbd0-ffffffff8143cbdb: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442a90)
Location: include/trace/events/ext4.h:422
Inline: True
```
**Symbols:**

```
ffffffff81442a90-ffffffff81442a9b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496730)
Location: include/trace/events/ext4.h:422
Inline: True
```
**Symbols:**

```
ffffffff81496730-ffffffff8149673b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521130)
Location: include/trace/events/ext4.h:428
Inline: True
```
**Symbols:**

```
ffffffff81521130-ffffffff81521145: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdab0)
Location: include/trace/events/ext4.h:430
Inline: True
```
**Symbols:**

```
ffffffff815bdab0-ffffffff815bdac5: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4830)
Location: include/trace/events/ext4.h:444
Inline: True
```
**Symbols:**

```
ffffffff815f4830-ffffffff815f4845: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d210)
Location: include/trace/events/ext4.h:444
Inline: True
```
**Symbols:**

```
ffffffff8162d210-ffffffff8162d225: __bpf_trace_ext4_writepages (STB_LOCAL)
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
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac0b8)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffff8000104ac0b8-ffff8000104ac0cc: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0673ed8)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
c0673ed8-c0673f00: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e36e0)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
c0000000005e36e0-c0000000005e370c: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d10e0)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813d10e0-ffffffff813d10eb: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1b60)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813c1b60-ffffffff813c1b6b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce570)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813ce570-ffffffff813ce57b: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_writepages(void *__data, struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e37c0)
Location: include/trace/events/ext4.h:391
Inline: False
```
**Symbols:**

```
ffffffff813e37c0-ffffffff813e37cb: __bpf_trace_ext4_writepages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

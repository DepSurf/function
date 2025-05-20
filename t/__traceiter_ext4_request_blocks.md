# Function: <code>__traceiter_ext4_request_blocks</code>

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
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81431860)
Location: include/trace/events/ext4.h:806
Inline: False
```
**Symbols:**

```
ffffffff81431860-ffffffff8143189d: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814383f0)
Location: include/trace/events/ext4.h:806
Inline: False
```
**Symbols:**

```
ffffffff814383f0-ffffffff8143842b: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148c070)
Location: include/trace/events/ext4.h:806
Inline: False
```
**Symbols:**

```
ffffffff8148c070-ffffffff8148c0ab: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8150ff90)
Location: include/trace/events/ext4.h:812
Inline: False
```
**Symbols:**

```
ffffffff8150ff90-ffffffff8150ffd3: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ab020)
Location: include/trace/events/ext4.h:814
Inline: False
```
**Symbols:**

```
ffffffff815ab020-ffffffff815ab063: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e19c0)
Location: include/trace/events/ext4.h:821
Inline: False
```
**Symbols:**

```
ffffffff815e19c0-ffffffff815e1a03: __traceiter_ext4_request_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_request_blocks(void *__data, struct ext4_allocation_request *ar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161a3c0)
Location: include/trace/events/ext4.h:818
Inline: False
```
**Symbols:**

```
ffffffff8161a3c0-ffffffff8161a403: __traceiter_ext4_request_blocks (STB_GLOBAL)
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

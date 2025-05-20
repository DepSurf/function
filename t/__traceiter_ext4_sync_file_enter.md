# Function: <code>__traceiter_ext4_sync_file_enter</code>

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
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81431950)
Location: include/trace/events/ext4.h:919
Inline: False
```
**Symbols:**

```
ffffffff81431950-ffffffff81431997: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814384e0)
Location: include/trace/events/ext4.h:919
Inline: False
```
**Symbols:**

```
ffffffff814384e0-ffffffff81438525: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148c160)
Location: include/trace/events/ext4.h:919
Inline: False
```
**Symbols:**

```
ffffffff8148c160-ffffffff8148c1a5: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815100a0)
Location: include/trace/events/ext4.h:925
Inline: False
```
**Symbols:**

```
ffffffff815100a0-ffffffff815100ef: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ab160)
Location: include/trace/events/ext4.h:927
Inline: False
```
**Symbols:**

```
ffffffff815ab160-ffffffff815ab1af: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e1b20)
Location: include/trace/events/ext4.h:934
Inline: False
```
**Symbols:**

```
ffffffff815e1b20-ffffffff815e1b6f: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_sync_file_enter(void *__data, struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161a520)
Location: include/trace/events/ext4.h:931
Inline: False
```
**Symbols:**

```
ffffffff8161a520-ffffffff8161a56f: __traceiter_ext4_sync_file_enter (STB_GLOBAL)
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

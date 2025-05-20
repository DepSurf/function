# Function: <code>__traceiter_ext4_journal_start</code>

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
int __traceiter_ext4_journal_start(void *__data, struct super_block *sb, int blocks, int rsv_blocks, int revoke_creds, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814324e0)
Location: include/trace/events/ext4.h:1799
Inline: False
```
**Symbols:**

```
ffffffff814324e0-ffffffff8143254b: __traceiter_ext4_journal_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start(void *__data, struct super_block *sb, int blocks, int rsv_blocks, int revoke_creds, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438f50)
Location: include/trace/events/ext4.h:1741
Inline: False
```
**Symbols:**

```
ffffffff81438f50-ffffffff81438fb9: __traceiter_ext4_journal_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start(void *__data, struct super_block *sb, int blocks, int rsv_blocks, int revoke_creds, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148cbd0)
Location: include/trace/events/ext4.h:1741
Inline: False
```
**Symbols:**

```
ffffffff8148cbd0-ffffffff8148cc39: __traceiter_ext4_journal_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start(void *__data, struct super_block *sb, int blocks, int rsv_blocks, int revoke_creds, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81510c70)
Location: include/trace/events/ext4.h:1747
Inline: False
```
**Symbols:**

```
ffffffff81510c70-ffffffff81510cef: __traceiter_ext4_journal_start (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>

# Function: <code>__traceiter_ext4_journal_start_reserved</code>

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
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81432550)
Location: include/trace/events/ext4.h:1827
Inline: False
```
**Symbols:**

```
ffffffff81432550-ffffffff814325a1: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438fc0)
Location: include/trace/events/ext4.h:1769
Inline: False
```
**Symbols:**

```
ffffffff81438fc0-ffffffff8143900f: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148cc40)
Location: include/trace/events/ext4.h:1769
Inline: False
```
**Symbols:**

```
ffffffff8148cc40-ffffffff8148cc8f: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81510cf0)
Location: include/trace/events/ext4.h:1775
Inline: False
```
**Symbols:**

```
ffffffff81510cf0-ffffffff81510d4b: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ac070)
Location: include/trace/events/ext4.h:1812
Inline: False
```
**Symbols:**

```
ffffffff815ac070-ffffffff815ac0cb: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e2bb0)
Location: include/trace/events/ext4.h:1819
Inline: False
```
**Symbols:**

```
ffffffff815e2bb0-ffffffff815e2c0b: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_journal_start_reserved(void *__data, struct super_block *sb, int blocks, long unsigned int IP);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161b5b0)
Location: include/trace/events/ext4.h:1816
Inline: False
```
**Symbols:**

```
ffffffff8161b5b0-ffffffff8161b60b: __traceiter_ext4_journal_start_reserved (STB_GLOBAL)
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

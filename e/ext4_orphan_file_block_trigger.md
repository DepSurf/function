# Function: <code>ext4_orphan_file_block_trigger</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_orphan_file_block_trigger(struct jbd2_buffer_trigger_type *triggers, struct buffer_head *bh, void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff814b1f10)
Location: fs/ext4/orphan.c:552
Inline: False
```
**Symbols:**

```
ffffffff814b1f10-ffffffff814b1ff5: ext4_orphan_file_block_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_orphan_file_block_trigger(struct jbd2_buffer_trigger_type *triggers, struct buffer_head *bh, void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff8153aaa0)
Location: fs/ext4/orphan.c:552
Inline: False
```
**Symbols:**

```
ffffffff8153aaa0-ffffffff8153abc1: ext4_orphan_file_block_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_orphan_file_block_trigger(struct jbd2_buffer_trigger_type *triggers, struct buffer_head *bh, void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff815d9050)
Location: fs/ext4/orphan.c:552
Inline: False
```
**Symbols:**

```
ffffffff815d9050-ffffffff815d9171: ext4_orphan_file_block_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_orphan_file_block_trigger(struct jbd2_buffer_trigger_type *triggers, struct buffer_head *bh, void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff81610bf0)
Location: fs/ext4/orphan.c:552
Inline: False
```
**Symbols:**

```
ffffffff81610bf0-ffffffff81610d11: ext4_orphan_file_block_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_orphan_file_block_trigger(struct jbd2_buffer_trigger_type *triggers, struct buffer_head *bh, void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff816499b0)
Location: fs/ext4/orphan.c:552
Inline: False
```
**Symbols:**

```
ffffffff816499b0-ffffffff81649ad1: ext4_orphan_file_block_trigger (STB_GLOBAL)
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

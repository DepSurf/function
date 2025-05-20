# Function: <code>out_of_line_wait_on_bit_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818209f0)
Location: kernel/sched/wait.c:445
Inline: False
Direct callers:
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff818209f0-ffffffff81820a93: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8189ae40)
Location: kernel/sched/wait.c:445
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff8189ae40-ffffffff8189aee3: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818cf470)
Location: kernel/sched/wait.c:442
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff818cf470-ffffffff818cf513: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81906a60)
Location: kernel/sched/wait_bit.c:110
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81906a60-ffffffff81906b06: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81990ad0)
Location: kernel/sched/wait_bit.c:110
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81990ad0-ffffffff81990b76: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819ed290)
Location: kernel/sched/wait_bit.c:110
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff819ed290-ffffffff819ed336: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a284c0)
Location: kernel/sched/wait_bit.c:110
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81a284c0-ffffffff81a28566: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a98cb0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81a98cb0-ffffffff81a98d53: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ad0600)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81ad0600-ffffffff81ad06a3: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81bc8f80)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81bc8f80-ffffffff81bc9023: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c41d70)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81c41d70-ffffffff81c41e13: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c33ce0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81c33ce0-ffffffff81c33d83: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81d526a0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81d526a0-ffffffff81d52743: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22b40)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff81f22b40-ffffffff81f22bee: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd4a0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff820cd4a0-ffffffff820cd54e: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151920)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff82151920-ffffffff821519ce: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234760)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
**Symbols:**

```
ffffffff82234760-ffffffff8223480e: out_of_line_wait_on_bit_lock (STB_GLOBAL)
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
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010da24f0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffff800010da24f0-ffff800010da25bc: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0e9a580)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
c0e9a580-c0e9a63c: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c000000000ee3a30)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
c000000000ee3a30-c000000000ee3afc: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0008c5aac)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffe0008c5aac-ffffffe0008c5b44: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a6f470)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81a6f470-ffffffff81a6f513: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a2b8a0)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81a2b8a0-ffffffff81a2b943: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81adb880)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81adb880-ffffffff81adb923: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ae7e20)
Location: kernel/sched/wait_bit.c:111
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
**Symbols:**

```
ffffffff81ae7e20-ffffffff81ae7ec3: out_of_line_wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

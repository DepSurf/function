# Function: <code>wb_start_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, long int nr_pages, bool range_cyclic, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123c3c0)
Location: fs/fs-writeback.c:922
Inline: True
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - fs/fs-writeback.c:wakeup_flusher_threads
```
**Symbols:**

```
ffffffff8123c3c0-ffffffff8123c485: wb_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, long int nr_pages, bool range_cyclic, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81264230)
Location: fs/fs-writeback.c:922
Inline: True
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - fs/fs-writeback.c:wakeup_flusher_threads
```
**Symbols:**

```
ffffffff81264230-ffffffff812642f2: wb_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, long int nr_pages, bool range_cyclic, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81277670)
Location: fs/fs-writeback.c:922
Inline: True
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - fs/fs-writeback.c:wakeup_flusher_threads
```
**Symbols:**

```
ffffffff81277670-ffffffff81277732: wb_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, long int nr_pages, bool range_cyclic, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81284a10)
Location: fs/fs-writeback.c:936
Inline: True
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - fs/fs-writeback.c:wakeup_flusher_threads
```
**Symbols:**

```
ffffffff81284a10-ffffffff81284ade: wb_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a33ab)
Location: fs/fs-writeback.c:947
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9dfb)
Location: fs/fs-writeback.c:948
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812de950)
Location: fs/fs-writeback.c:974
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff812de950-ffffffff812de980: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd040)
Location: fs/fs-writeback.c:989
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff812fd040-ffffffff812fd070: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f530)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff8130f530-ffffffff8130f560: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134ec92)
Location: fs/fs-writeback.c:1077
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135bb12)
Location: fs/fs-writeback.c:1077
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81362722)
Location: fs/fs-writeback.c:1083
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b0f22)
Location: fs/fs-writeback.c:1222
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81435db6)
Location: fs/fs-writeback.c:1188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bf930)
Location: fs/fs-writeback.c:1191
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff814bf930-ffffffff814bf974: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f4a30)
Location: fs/fs-writeback.c:1196
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff814f4a30-ffffffff814f4a74: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81529140)
Location: fs/fs-writeback.c:1213
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff81529140-ffffffff81529184: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c6f28)
Location: fs/fs-writeback.c:1077
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a1914)
Location: fs/fs-writeback.c:1077
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4730)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
c0000000004c4730-c0000000004c4788: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe0002841ba)
Location: fs/fs-writeback.c:1077
Inline: True
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
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307b10)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff81307b10-ffffffff81307b40: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8730)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff812f8730-ffffffff812f8760: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305900)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff81305900-ffffffff81305930: wb_start_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback *wb, enum wb_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81316c70)
Location: fs/fs-writeback.c:1077
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
**Symbols:**

```
ffffffff81316c70-ffffffff81316ca0: wb_start_writeback (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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

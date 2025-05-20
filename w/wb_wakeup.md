# Function: <code>wb_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81235ca0)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
```
**Symbols:**

```
ffffffff81235ca0-ffffffff81235ced: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125f600)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8125f600-ffffffff8125f64d: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81272b20)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81272b20-ffffffff81272b6d: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8127ffe0)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8127ffe0-ffffffff8128002d: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a2ad0)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812a2ad0-ffffffff812a2b1d: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c96f0)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812c96f0-ffffffff812c974a: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812de8f0)
Location: fs/fs-writeback.c:168
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812de8f0-ffffffff812de94a: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fcfe0)
Location: fs/fs-writeback.c:169
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812fcfe0-ffffffff812fd03a: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f4d0)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8130f4d0-ffffffff8130f52a: wb_wakeup (STB_LOCAL)
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
In fs/fs-writeback.c (ffffffff8134914b)
Location: fs/fs-writeback.c:153
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
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
In fs/fs-writeback.c (ffffffff813560ab)
Location: fs/fs-writeback.c:153
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
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
In fs/fs-writeback.c (ffffffff8135cc9b)
Location: fs/fs-writeback.c:153
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
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
In fs/fs-writeback.c (ffffffff813ab07b)
Location: fs/fs-writeback.c:134
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
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
In fs/fs-writeback.c (ffffffff81431ea0)
Location: fs/fs-writeback.c:135
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bf8a0)
Location: fs/fs-writeback.c:136
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff814bf8a0-ffffffff814bf916: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f49a0)
Location: fs/fs-writeback.c:136
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff814f49a0-ffffffff814f4a16: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff815290b0)
Location: fs/fs-writeback.c:136
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff815290b0-ffffffff81529126: wb_wakeup (STB_LOCAL)
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
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c6e10)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffff8000103c6e10-ffff8000103c6ed4: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a103c)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c05a103c-c05a1098: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4670)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c0000000004c4670-c0000000004c4724: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000283c04)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffe000283c04-ffffffe000283c60: wb_wakeup (STB_LOCAL)
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
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307ab0)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81307ab0-ffffffff81307b0a: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f86d0)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812f86d0-ffffffff812f872a: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813058a0)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff813058a0-ffffffff813058fa: wb_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wb_wakeup(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81316c10)
Location: fs/fs-writeback.c:152
Inline: False
Direct callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81316c10-ffffffff81316c6a: wb_wakeup (STB_LOCAL)
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

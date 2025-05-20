# Function: <code>queue_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81236260)
Location: fs/fs-writeback.c:1108
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff816a08f0)
Location: drivers/md/dm.c:723
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81236260-ffffffff81236350: queue_io (STB_LOCAL)
ffffffff816a08f0-ffffffff816a0964: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125fbd0)
Location: fs/fs-writeback.c:1145
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81701c40)
Location: drivers/md/dm.c:557
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8125fbd0-ffffffff8125fcbd: queue_io (STB_LOCAL)
ffffffff81701c40-ffffffff81701cb4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812730f0)
Location: fs/fs-writeback.c:1145
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81733a90)
Location: drivers/md/dm.c:557
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812730f0-ffffffff812731dd: queue_io (STB_LOCAL)
ffffffff81733a90-ffffffff81733b04: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81280500)
Location: fs/fs-writeback.c:1159
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff8174cbd0)
Location: drivers/md/dm.c:555
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81280500-ffffffff812805ed: queue_io (STB_LOCAL)
ffffffff8174cbd0-ffffffff8174cc44: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a3030)
Location: fs/fs-writeback.c:1162
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff817bedb0)
Location: drivers/md/dm.c:562
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812a3030-ffffffff812a3120: queue_io (STB_LOCAL)
ffffffff817bedb0-ffffffff817bee24: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9a80)
Location: fs/fs-writeback.c:1163
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81807340)
Location: drivers/md/dm.c:654
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812c9a80-ffffffff812c9b6d: queue_io (STB_LOCAL)
ffffffff81807340-ffffffff818073b4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812decb0)
Location: fs/fs-writeback.c:1189
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81833370)
Location: drivers/md/dm.c:709
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812decb0-ffffffff812ded9d: queue_io (STB_LOCAL)
ffffffff81833370-ffffffff818333e4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd360)
Location: fs/fs-writeback.c:1204
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff818752a0)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812fd360-ffffffff812fd451: queue_io (STB_LOCAL)
ffffffff818752a0-ffffffff81875314: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f850)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff818a7050)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8130f850-ffffffff8130f941: queue_io (STB_LOCAL)
ffffffff818a7050-ffffffff818a70c4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134a1c0)
Location: fs/fs-writeback.c:1298
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81979a11)
Location: drivers/md/dm.c:702
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8134a1c0-ffffffff8134a2e3: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813570f0)
Location: fs/fs-writeback.c:1296
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff8197e35e)
Location: drivers/md/dm.c:698
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff813570f0-ffffffff813571f1: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135daa0)
Location: fs/fs-writeback.c:1302
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81962111)
Location: drivers/md/dm.c:703
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8135daa0-ffffffff8135dba1: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ac180)
Location: fs/fs-writeback.c:1445
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81a0b251)
Location: drivers/md/dm.c:583
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_dec_pending
```
**Symbols:**

```
ffffffff813ac180-ffffffff813ac29a: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81432220)
Location: fs/fs-writeback.c:1416
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81b72df1)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_complete
```
**Symbols:**

```
ffffffff81432220-ffffffff81432359: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c0290)
Location: fs/fs-writeback.c:1427
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81d0fbb1)
Location: drivers/md/dm.c:661
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
```
**Symbols:**

```
ffffffff814c0290-ffffffff814c03ac: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f5450)
Location: fs/fs-writeback.c:1432
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81d7902e)
Location: drivers/md/dm.c:668
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
```
**Symbols:**

```
ffffffff814f5450-ffffffff814f556c: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work, long unsigned int dirtied_before);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81529b60)
Location: fs/fs-writeback.c:1449
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff81e3019d)
Location: drivers/md/dm.c:670
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
```
**Symbols:**

```
ffffffff81529b60-ffffffff81529c7c: queue_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c6cd0)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffff800010afce88)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffff8000103c6cd0-ffff8000103c6e10: queue_io (STB_LOCAL)
ffff800010afce88-ffff800010afcf64: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a16d4)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (c0bdc950)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
c05a16d4-c05a1808: queue_io (STB_LOCAL)
c0bdc950-c0bdc9b4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c50e0)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (c000000000bea8c0)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
c0000000004c50e0-c0000000004c525c: queue_io (STB_LOCAL)
c000000000bea8c0-c000000000bea9a4: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000283f66)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffe0006ed5f4)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffe000283f66-ffffffe000284058: queue_io (STB_LOCAL)
ffffffe0006ed5f4-ffffffe0006ed662: queue_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307e30)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff8184ced0)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81307e30-ffffffff81307f21: queue_io (STB_LOCAL)
ffffffff8184ced0-ffffffff8184cf44: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8a50)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff818144f0)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff812f8a50-ffffffff812f8b41: queue_io (STB_LOCAL)
ffffffff818144f0-ffffffff81814564: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305c20)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff8189c500)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81305c20-ffffffff81305d11: queue_io (STB_LOCAL)
ffffffff8189c500-ffffffff8189c574: queue_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void queue_io(struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81317160)
Location: fs/fs-writeback.c:1292
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_writeback
```
```
In drivers/md/dm.c (ffffffff818b8740)
Location: drivers/md/dm.c:689
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81317160-ffffffff8131725f: queue_io (STB_LOCAL)
ffffffff818b8740-ffffffff818b87b4: queue_io (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int dirtied_before</code>
</li>
</ul>
</details>
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

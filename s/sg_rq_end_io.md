# Function: <code>sg_rq_end_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c4100)
Location: drivers/scsi/sg.c:1285
Inline: False
```
**Symbols:**

```
ffffffff815c4100-ffffffff815c4433: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161c910)
Location: drivers/scsi/sg.c:1286
Inline: False
```
**Symbols:**

```
ffffffff8161c910-ffffffff8161cc44: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164d520)
Location: drivers/scsi/sg.c:1279
Inline: False
```
**Symbols:**

```
ffffffff8164d520-ffffffff8164d854: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816608a0)
Location: drivers/scsi/sg.c:1294
Inline: False
```
**Symbols:**

```
ffffffff816608a0-ffffffff81660c59: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816cb830)
Location: drivers/scsi/sg.c:1293
Inline: False
```
**Symbols:**

```
ffffffff816cb830-ffffffff816cbbed: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1330
Inline: False
```
**Symbols:**

```
ffffffff81708170-ffffffff81708514: sg_rq_end_io (STB_LOCAL)
ffffffff8170aaf7-ffffffff8170ab0f: sg_rq_end_io.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1321
Inline: False
```
**Symbols:**

```
ffffffff81728b30-ffffffff81728ed0: sg_rq_end_io (STB_LOCAL)
ffffffff8172cecc-ffffffff8172cee4: sg_rq_end_io.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81764df0-ffffffff8176518c: sg_rq_end_io (STB_LOCAL)
ffffffff81768735-ffffffff81768773: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81788de0-ffffffff81789180: sg_rq_end_io (STB_LOCAL)
ffffffff8178c725-ffffffff8178c73d: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1339
Inline: False
```
**Symbols:**

```
ffffffff8184d5f0-ffffffff8184d99d: sg_rq_end_io (STB_LOCAL)
ffffffff8185124d-ffffffff81851265: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1339
Inline: False
```
**Symbols:**

```
ffffffff8185d9e0-ffffffff8185dd8d: sg_rq_end_io (STB_LOCAL)
ffffffff81c16e29-ffffffff81c16e41: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1338
Inline: False
```
**Symbols:**

```
ffffffff81840660-ffffffff81840a0d: sg_rq_end_io (STB_LOCAL)
ffffffff81c08b71-ffffffff81c08b89: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1321
Inline: False
```
**Symbols:**

```
ffffffff818cd1b0-ffffffff818cd55c: sg_rq_end_io (STB_LOCAL)
ffffffff81d0d33a-ffffffff81d0d352: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1315
Inline: False
```
**Symbols:**

```
ffffffff81a1b890-ffffffff81a1bc4e: sg_rq_end_io (STB_LOCAL)
ffffffff81ed6311-ffffffff81ed6329: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum rq_end_io_ret sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9ca20)
Location: drivers/scsi/sg.c:1315
Inline: False
```
**Symbols:**

```
ffffffff81b9ca20-ffffffff81b9cdf6: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum rq_end_io_ret sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf3000)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81bf3000-ffffffff81bf33d7: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum rq_end_io_ret sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c488f0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81c488f0-ffffffff81c48cc7: sg_rq_end_io (STB_LOCAL)
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
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffff800010990b40)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffff800010990b40-ffff800010990ec0: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a615dc)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
c0a615dc-c0a61900: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a51540)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
c000000000a51540-c000000000a51928: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f34ba)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffe0005f34ba-ffffffe0005f3764: sg_rq_end_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff8173d4d0-ffffffff8173d870: sg_rq_end_io (STB_LOCAL)
ffffffff81740e15-ffffffff81740e2d: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff8171f170-ffffffff8171f510: sg_rq_end_io (STB_LOCAL)
ffffffff81722aa5-ffffffff81722abd: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff8177dc60-ffffffff8177e000: sg_rq_end_io (STB_LOCAL)
ffffffff817815a5-ffffffff817815bd: sg_rq_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81797a70-ffffffff81797e10: sg_rq_end_io (STB_LOCAL)
ffffffff8179b38b-ffffffff8179b3a3: sg_rq_end_io.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_status_t status</code>
</li>
<li>
<b>Param removed. </b>
<code>int uptodate</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>enum rq_end_io_ret</code>
</li>
</ul>
</details>
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

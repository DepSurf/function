# Function: <code>blk_unprep_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b4680)
Location: block/blk-core.c:2710
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff813b4680-ffffffff813b46a9: blk_unprep_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe4aa)
Location: block/blk-core.c:2682
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff813f8370-ffffffff813f8399: blk_unprep_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417e60)
Location: block/blk-core.c:2673
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81411d40-ffffffff81411d68: blk_unprep_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425c16)
Location: block/blk-core.c:2814
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8141fb80-ffffffff8141fba9: blk_unprep_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450d86)
Location: block/blk-core.c:3038
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8144a6f0-ffffffff8144a71c: blk_unprep_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_unprep_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484034)
Location: block/blk-core.c:3182
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8147d950-ffffffff8147d97a: blk_unprep_request (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
</ul>

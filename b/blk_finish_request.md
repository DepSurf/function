# Function: <code>blk_finish_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba6c0)
Location: block/blk-core.c:2723
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_bidi_request
  - block/blk-core.c:__blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff813ba6c0-ffffffff813ba7a4: blk_finish_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe440)
Location: block/blk-core.c:2695
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff813fe440-ffffffff813fe52a: blk_finish_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417dd0)
Location: block/blk-core.c:2686
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81417dd0-ffffffff81417f09: blk_finish_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425bb0)
Location: block/blk-core.c:2824
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81425bb0-ffffffff81425ce6: blk_finish_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450d20)
Location: block/blk-core.c:3048
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81450d20-ffffffff81450e5f: blk_finish_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_finish_request(struct request *req, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483fc0)
Location: block/blk-core.c:3192
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81483fc0-ffffffff81484117: blk_finish_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
</ul>

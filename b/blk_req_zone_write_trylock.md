# Function: <code>blk_req_zone_write_trylock</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815789e0)
Location: block/blk-zoned.c:85
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff815789e0-ffffffff81578a4b: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595590)
Location: block/blk-zoned.c:85
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81595590-ffffffff815955f1: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c1e0)
Location: block/blk-zoned.c:77
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff8159c1e0-ffffffff8159c242: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (ffffffff81604847)
Location: block/blk-zoned.c:77
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81cda388-ffffffff81cda3b0: blk_req_zone_write_trylock.cold (STB_LOCAL)
ffffffff81604810-ffffffff81604888: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (ffffffff816b7fc7)
Location: block/blk-zoned.c:76
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81e8df65-ffffffff81e8df8d: blk_req_zone_write_trylock.cold (STB_LOCAL)
ffffffff816b7f90-ffffffff816b8014: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:73
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff82077302-ffffffff82077331: blk_req_zone_write_trylock.cold (STB_LOCAL)
ffffffff81778590-ffffffff8177861f: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff820f736c-ffffffff820f739b: blk_req_zone_write_trylock.cold (STB_LOCAL)
ffffffff817b8230-ffffffff817b82bf: blk_req_zone_write_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool blk_req_zone_write_trylock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff821d4bf3-ffffffff821d4c25: blk_req_zone_write_trylock.cold (STB_LOCAL)
ffffffff817fcae0-ffffffff817fcb8d: blk_req_zone_write_trylock (STB_GLOBAL)
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

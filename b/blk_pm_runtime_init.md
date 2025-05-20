# Function: <code>blk_pm_runtime_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5cc0)
Location: block/blk-core.c:3391
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff813b5cc0-ffffffff813b5cff: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fab90)
Location: block/blk-core.c:3364
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff813fab90-ffffffff813fabcf: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814144f0)
Location: block/blk-core.c:3322
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff814144f0-ffffffff8141452f: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422250)
Location: block/blk-core.c:3427
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81422250-ffffffff8142229e: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d0d0)
Location: block/blk-core.c:3651
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8144d0d0-ffffffff8144d11e: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480340)
Location: block/blk-core.c:3780
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81480340-ffffffff81480396: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d5e30)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff814d5e30-ffffffff814d5e6f: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501c80)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81501c80-ffffffff81501cbf: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fbb0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8151fbb0-ffffffff8151fbef: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580b30)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81580b30-ffffffff81580b72: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8159db70)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8159db70-ffffffff8159dbb2: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815a47b0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815a47b0-ffffffff815a47f2: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8160d1a0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8160d1a0-ffffffff8160d1e2: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c1330)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816c1330-ffffffff816c137a: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81782410)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81782410-ffffffff8178245a: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c2540)
Location: block/blk-pm.c:29
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817c2540-ffffffff817c258a: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff818072a0)
Location: block/blk-pm.c:29
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff818072a0-ffffffff818072ea: blk_pm_runtime_init (STB_GLOBAL)
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
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff8000106288c8)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffff8000106288c8-ffff800010628910: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07cffec)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c07cffec-c07d002c: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca3c0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c0000000007ca3c0-c0000000007ca428: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe000459d96)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffe000459d96-ffffffe000459ddc: blk_pm_runtime_init (STB_GLOBAL)
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
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81518190)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81518190-ffffffff815181cf: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815084a0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815084a0-ffffffff815084df: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81514220)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81514220-ffffffff8151425f: blk_pm_runtime_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_pm_runtime_init(struct request_queue *q, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152d9e0)
Location: block/blk-pm.c:31
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8152d9e0-ffffffff8152da1f: blk_pm_runtime_init (STB_GLOBAL)
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

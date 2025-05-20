# Function: <code>blk_dump_rq_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b67d0)
Location: block/blk-core.c:158
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff813b67d0-ffffffff813b68b5: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fb630)
Location: block/blk-core.c:158
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff813fb630-ffffffff813fb726: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414dd0)
Location: block/blk-core.c:159
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff81414dd0-ffffffff81414ec7: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422530)
Location: block/blk-core.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81422530-ffffffff814225d3: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d620)
Location: block/blk-core.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8144d620-ffffffff8144d6c3: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81485690)
Location: block/blk-core.c:280
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81485690-ffffffff81485708: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149ff40)
Location: block/blk-core.c:199
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8149ff40-ffffffff8149ffb8: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cdf8e)
Location: block/blk-core.c:242
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814cdf8e-ffffffff814ce006: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e72ae)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814e72ae-ffffffff814e7326: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815462b6)
Location: block/blk-core.c:264
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff815462b6-ffffffff8154632e: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81bf260d)
Location: block/blk-core.c:267
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81bf260d-ffffffff81bf2685: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81be453f)
Location: block/blk-core.c:268
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81be453f-ffffffff81be45b7: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81cd7fe1)
Location: block/blk-core.c:263
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81cd7fe1-ffffffff81cd8059: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81e8b80d)
Location: block/blk-mq.c:653
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81e8b80d-ffffffff81e8b88f: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81743b80)
Location: block/blk-mq.c:759
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81743b80-ffffffff81743c60: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177f450)
Location: block/blk-mq.c:746
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8177f450-ffffffff8177f52d: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c1f40)
Location: block/blk-mq.c:751
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff817c1f40-ffffffff817c201a: blk_dump_rq_flags (STB_GLOBAL)
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
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4e9c)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffff8000105e4e9c-ffff8000105e4f40: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791eec)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
c0791eec-c0791f90: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778cfc)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
c000000000778cfc-c000000000778dc4: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004262e4)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffe0004262e4-ffffffe00042637e: blk_dump_rq_flags (STB_GLOBAL)
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
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df88e)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814df88e-ffffffff814df906: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d022e)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814d022e-ffffffff814d02a6: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db91e)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814db91e-ffffffff814db996: blk_dump_rq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_dump_rq_flags(struct request *rq, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f478e)
Location: block/blk-core.c:245
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_request
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff814f478e-ffffffff814f4806: blk_dump_rq_flags (STB_GLOBAL)
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

# Function: <code>put_io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff813bee60)
Location: block/blk-ioc.c:129
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/bio.c:bio_disassociate_task
  - block/ioprio.c:set_task_ioprio
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff813bee60-ffffffff813beee1: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81402ba0)
Location: block/blk-ioc.c:129
Inline: False
Direct callers:
  - block/bio.c:bio_disassociate_task
  - block/ioprio.c:set_task_ioprio
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff81402ba0-ffffffff81402c22: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8141c8d0)
Location: block/blk-ioc.c:129
Inline: False
Direct callers:
  - block/bio.c:bio_disassociate_task
  - block/blk-core.c:__blk_put_request
  - block/ioprio.c:set_task_ioprio
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff8141c8d0-ffffffff8141c952: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142aad0)
Location: block/blk-ioc.c:137
Inline: True
Direct callers:
  - block/bio.c:bio_disassociate_task
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff8142aad0-ffffffff8142ab53: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81455cc0)
Location: block/blk-ioc.c:138
Inline: True
Direct callers:
  - block/bio.c:bio_disassociate_task
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff81455cc0-ffffffff81455d4a: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81489040)
Location: block/blk-ioc.c:138
Inline: True
Direct callers:
  - block/bio.c:bio_disassociate_task
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff81489040-ffffffff814890c9: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814a2f70)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814a2f70-ffffffff814a2ff9: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d1020)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814d1020-ffffffff814d10b2: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814ea3e0)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814ea3e0-ffffffff814ea472: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81549380)
Location: block/blk-ioc.c:136
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff81549380-ffffffff81549418: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815651a0)
Location: block/blk-ioc.c:142
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff815651a0-ffffffff81565238: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8156d810)
Location: block/blk-ioc.c:142
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff8156d810-ffffffff8156d8a8: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815d1e00)
Location: block/blk-ioc.c:142
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff815d1e00-ffffffff815d1e98: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8167dca0)
Location: block/blk-ioc.c:209
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:exit_io_context
```
**Symbols:**

```
ffffffff8167dca0-ffffffff8167dd50: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8173a8e0)
Location: block/blk-ioc.c:209
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:exit_io_context
```
**Symbols:**

```
ffffffff8173a8e0-ffffffff8173a990: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81776fe0)
Location: block/blk-ioc.c:205
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:exit_io_context
```
**Symbols:**

```
ffffffff81776fe0-ffffffff81777090: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817b9210)
Location: block/blk-ioc.c:205
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:exit_io_context
```
**Symbols:**

```
ffffffff817b9210-ffffffff817b92c0: put_io_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e8830)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffff8000105e8830-ffff8000105e8944: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c0795194)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c0795194-c0795250: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c00000000077d480)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c00000000077d480-c00000000077d590: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe00042938c)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffe00042938c-ffffffe000429422: put_io_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814e29c0)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814e29c0-ffffffff814e2a52: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d3350)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814d3350-ffffffff814d33e2: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814dea50)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814dea50-ffffffff814deae2: put_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_io_context(struct io_context *ioc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814f78c0)
Location: block/blk-ioc.c:135
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814f78c0-ffffffff814f7952: put_io_context (STB_GLOBAL)
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

# Function: <code>create_task_io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff813bf080)
Location: block/blk-ioc.c:234
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff813bf080-ffffffff813bf17d: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81402fd0)
Location: block/blk-ioc.c:234
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff81402fd0-ffffffff814030c1: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8141cd00)
Location: block/blk-ioc.c:234
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff8141cd00-ffffffff8141cdf1: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142ad60)
Location: block/blk-ioc.c:265
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff8142ad60-ffffffff8142ae51: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81455f50)
Location: block/blk-ioc.c:266
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request_flags
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff81455f50-ffffffff81456041: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81489390)
Location: block/blk-ioc.c:266
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81489390-ffffffff81489488: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814a31e0)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814a31e0-ffffffff814a32d8: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d12a0)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814d12a0-ffffffff814d13ae: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814ea650)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814ea650-ffffffff814ea75e: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815495f0)
Location: block/blk-ioc.c:250
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff815495f0-ffffffff815496fe: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81565420)
Location: block/blk-ioc.c:250
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff81565420-ffffffff8156552e: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8156da90)
Location: block/blk-ioc.c:250
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff8156da90-ffffffff8156db9e: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815d2080)
Location: block/blk-ioc.c:250
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff815d2080-ffffffff815d218e: create_task_io_context (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e8d18)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffff8000105e8d18-ffff8000105e8e54: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c079547c)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
c079547c-c0795584: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c00000000077d8c0)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
c00000000077d8c0-c00000000077da50: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe00042962e)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffe00042962e-ffffffe00042973c: create_task_io_context (STB_GLOBAL)
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
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814e2c30)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814e2c30-ffffffff814e2d3e: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d35c0)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814d35c0-ffffffff814d36ce: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814decc0)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814decc0-ffffffff814dedce: create_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int create_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814f7b30)
Location: block/blk-ioc.c:243
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-ioc.c:get_task_io_context
```
**Symbols:**

```
ffffffff814f7b30-ffffffff814f7c3c: create_task_io_context (STB_GLOBAL)
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

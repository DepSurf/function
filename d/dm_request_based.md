# Function: <code>dm_request_based</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1ee9)
Location: drivers/md/dm.c:1788
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff816a31e0-ffffffff816a3200: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170fb80)
Location: drivers/md/dm-rq.c:61
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8170fb80-ffffffff8170fba0: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81741b80)
Location: drivers/md/dm-rq.c:57
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81741b80-ffffffff81741ba0: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175b5d0)
Location: drivers/md/dm-rq.c:57
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8175b5d0-ffffffff8175b5f0: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cd820)
Location: drivers/md/dm-rq.c:57
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff817cd820-ffffffff817cd84d: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81816610)
Location: drivers/md/dm-rq.c:57
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81816610-ffffffff81816640: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81842180)
Location: drivers/md/dm-rq.c:44
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff81842180-ffffffff8184219d: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81884fe0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff81884fe0-ffffffff81884ffd: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b6f60)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff818b6f60-ffffffff818b6f7d: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81987910)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff81987910-ffffffff8198792d: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b8a0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8198b8a0-ffffffff8198b8bd: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196ff90)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8196ff90-ffffffff8196ffad: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a188a0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81a188a0-ffffffff81a188bd: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b81660)
Location: drivers/md/dm-rq.c:59
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81b81660-ffffffff81b81683: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1fa00)
Location: drivers/md/dm-rq.c:58
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81d1fa00-ffffffff81d1fa23: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88bf0)
Location: drivers/md/dm-rq.c:59
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81d88bf0-ffffffff81d88c13: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e40300)
Location: drivers/md/dm-rq.c:59
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81e40300-ffffffff81e40323: dm_request_based (STB_GLOBAL)
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
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0ef70)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffff800010b0ef70-ffff800010b0efa4: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0bed31c)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
c0bed31c-c0bed344: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c022c0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
c000000000c022c0-c000000000c022dc: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fc130)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffe0006fc130-ffffffe0006fc158: dm_request_based (STB_GLOBAL)
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
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185cde0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff8185cde0-ffffffff8185cdfd: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818243b0)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff818243b0-ffffffff818243cd: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818ac410)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff818ac410-ffffffff818ac42d: dm_request_based (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_request_based(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c8660)
Location: drivers/md/dm-rq.c:60
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff818c8660-ffffffff818c867d: dm_request_based (STB_GLOBAL)
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

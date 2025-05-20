# Function: <code>blk_mq_request_issue_directly</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814913a0)
Location: block/blk-mq.c:1738
Inline: False
```
**Symbols:**

```
ffffffff814913a0-ffffffff81491455: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8ec0)
Location: block/blk-mq.c:1873
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814d8ec0-ffffffff814d8f97: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2280)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814f2280-ffffffff814f2357: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552a0d)
Location: block/blk-mq.c:1953
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
```
**Symbols:**

```
ffffffff815528c0-ffffffff81552997: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156ebfa)
Location: block/blk-mq.c:2050
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff8156ea10-ffffffff8156eaa4: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815767da)
Location: block/blk-mq.c:2074
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff815765f0-ffffffff81576684: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815db42e)
Location: block/blk-mq.c:2085
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff815db200-ffffffff815db2de: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81688112)
Location: block/blk-mq.c:2543
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817464f8)
Location: block/blk-mq.c:2686
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782a90)
Location: block/blk-mq.c:2663
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
```
**Symbols:**

```
ffffffff81782a90-ffffffff81782b0e: blk_mq_request_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4de0)
Location: block/blk-mq.c:2685
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
```
**Symbols:**

```
ffffffff817c4de0-ffffffff817c4e5b: blk_mq_request_issue_directly (STB_LOCAL)
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
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1ab0)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffff8000105f1ab0-ffff8000105f1bac: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079db90)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
c079db90-c079dcac: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788970)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
c000000000788970-c000000000788ac4: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430510)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffe000430510-ffffffe0004305c0: blk_mq_request_issue_directly (STB_GLOBAL)
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
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ea860)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814ea860-ffffffff814ea937: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dadb0)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814dadb0-ffffffff814dae87: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e68f0)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814e68f0-ffffffff814e69c7: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request *rq, bool last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ff900)
Location: block/blk-mq.c:1893
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff814ff900-ffffffff814ff97e: blk_mq_request_issue_directly (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

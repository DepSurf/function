# Function: <code>__blk_mq_issue_directly</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814903fb)
Location: block/blk-mq.c:1642
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa778)
Location: block/blk-mq.c:1769
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d825f)
Location: block/blk-mq.c:1774
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f1611)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154fdb1)
Location: block/blk-mq.c:1842
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c410)
Location: block/blk-mq.c:1939
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573b91)
Location: block/blk-mq.c:1959
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da5b1)
Location: block/blk-mq.c:1970
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff81687ef7)
Location: block/blk-mq.c:2443
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff817462c7)
Location: block/blk-mq.c:2586
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t __blk_mq_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177f100)
Location: block/blk-mq.c:2574
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff8177f100-ffffffff8177f1be: __blk_mq_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t __blk_mq_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c1020)
Location: block/blk-mq.c:2596
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff817c1020-ffffffff817c10de: __blk_mq_issue_directly (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0cc0)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ccec)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787840)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f9c0)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9bf1)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da151)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5c81)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fec11)
Location: block/blk-mq.c:1794
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

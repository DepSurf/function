# Function: <code>mmc_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816beb90)
Location: drivers/mmc/core/core.c:227
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:__mmc_start_req
```
**Symbols:**

```
ffffffff816beb90-ffffffff816bee0b: mmc_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817215d0)
Location: drivers/mmc/core/core.c:228
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:__mmc_start_req
```
**Symbols:**

```
ffffffff817215d0-ffffffff8172182b: mmc_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817544e0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff817544e0-ffffffff8175474a: mmc_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81772290)
Location: drivers/mmc/core/core.c:336
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff81772290-ffffffff817724e3: mmc_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e8250)
Location: drivers/mmc/core/core.c:340
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff817e8250-ffffffff817e82db: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81831680)
Location: drivers/mmc/core/core.c:337
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81831680-ffffffff8183172c: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185d660)
Location: drivers/mmc/core/core.c:337
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff8185d660-ffffffff8185d70c: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818a3d23-ffffffff818a3d36: mmc_start_request.cold (STB_LOCAL)
ffffffff818a12b0-ffffffff818a135f: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d35a0)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818d35a0-ffffffff818d364f: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a5ca0)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff819a5ca0-ffffffff819a5d4f: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8a50)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff819a8a50-ffffffff819a8aff: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198d720)
Location: drivers/mmc/core/core.c:336
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff8198d720-ffffffff8198d7cf: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a38d70)
Location: drivers/mmc/core/core.c:336
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81a38d70-ffffffff81a38e1f: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba5e00)
Location: drivers/mmc/core/core.c:336
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81ba5e00-ffffffff81ba5eb3: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d48130)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81d48130-ffffffff81d481e3: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db2a30)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81db2a30-ffffffff81db2ae3: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6adc0)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81e6adc0-ffffffff81e6ae73: mmc_start_request (STB_GLOBAL)
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
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ca58)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffff800010b2ca58-ffff800010b2cb14: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c07dac)
Location: drivers/mmc/core/core.c:335
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
c0c07dac-c0c07e78: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c257c0)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
c000000000c257c0-c000000000c258b0: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706ad2)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffffffe000706ad2-ffffffe000706b82: mmc_start_request (STB_GLOBAL)
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
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81876f60)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81876f60-ffffffff8187700f: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c8400)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818c8400-ffffffff818c84af: mmc_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e4f20)
Location: drivers/mmc/core/core.c:335
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818e4f20-ffffffff818e4fcf: mmc_start_request (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

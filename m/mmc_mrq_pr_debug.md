# Function: <code>mmc_mrq_pr_debug</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817722c1)
Location: drivers/mmc/core/core.c:266
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6330)
Location: drivers/mmc/core/core.c:269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff817e6330-ffffffff817e64eb: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182f700)
Location: drivers/mmc/core/core.c:266
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8182f700-ffffffff8182f8b0: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185b970)
Location: drivers/mmc/core/core.c:266
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8185b970-ffffffff8185bb20: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8189f800)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8189f800-ffffffff8189f9ac: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d1da0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818d1da0-ffffffff818d1f4c: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a44f0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff819a44f0-ffffffff819a469c: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7570)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff819a7570-ffffffff819a771c: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c200)
Location: drivers/mmc/core/core.c:265
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8198c200-ffffffff8198c3ac: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a375c0)
Location: drivers/mmc/core/core.c:265
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81a375c0-ffffffff81a37763: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba4160)
Location: drivers/mmc/core/core.c:265
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81ba4160-ffffffff81ba431a: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d462b0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81d462b0-ffffffff81d46467: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db0a60)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81db0a60-ffffffff81db0c38: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e68df0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81e68df0-ffffffff81e68fc8: mmc_mrq_pr_debug (STB_LOCAL)
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
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ae20)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffff800010b2ae20-ffff800010b2afc0: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0666c)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
```
**Symbols:**

```
c0c0666c-c0c06884: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23680)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
c000000000c23680-c000000000c238d8: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe0007051e0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffe0007051e0-ffffffe000705376: mmc_mrq_pr_debug (STB_LOCAL)
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
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875760)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81875760-ffffffff8187590c: mmc_mrq_pr_debug (STB_LOCAL)
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
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c6c00)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818c6c00-ffffffff818c6dac: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host *host, struct mmc_request *mrq, bool cqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e36b0)
Location: drivers/mmc/core/core.c:264
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818e36b0-ffffffff818e385c: mmc_mrq_pr_debug (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

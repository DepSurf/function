# Function: <code>mmc_mrq_prep</code>

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
In drivers/mmc/core/core.c (ffffffff81772307)
Location: drivers/mmc/core/core.c:296
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6550)
Location: drivers/mmc/core/core.c:303
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff817e6550-ffffffff817e665a: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182f8d0)
Location: drivers/mmc/core/core.c:300
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8182f8d0-ffffffff8182f9d6: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185bb40)
Location: drivers/mmc/core/core.c:300
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8185bb40-ffffffff8185bc46: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8189fa00)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8189fa00-ffffffff8189faf5: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d1f70)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818d1f70-ffffffff818d2065: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a46c0)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff819a46c0-ffffffff819a47b5: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7740)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff819a7740-ffffffff819a7835: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c3d0)
Location: drivers/mmc/core/core.c:299
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff8198c3d0-ffffffff8198c4c5: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a37a50)
Location: drivers/mmc/core/core.c:299
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81a37a50-ffffffff81a37b45: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba4600)
Location: drivers/mmc/core/core.c:299
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81ba4600-ffffffff81ba4705: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d46790)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81d46790-ffffffff81d46895: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db0f60)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81db0f60-ffffffff81db1065: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e692f0)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81e692f0-ffffffff81e693f5: mmc_mrq_prep (STB_LOCAL)
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
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2aff0)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffff800010b2aff0-ffff800010b2b11c: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c068a4)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
```
**Symbols:**

```
c0c068a4-c0c069cc: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23920)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
c000000000c23920-c000000000c23ab0: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe0007053a2)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffe0007053a2-ffffffe00070546e: mmc_mrq_prep (STB_LOCAL)
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
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875930)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff81875930-ffffffff81875a25: mmc_mrq_prep (STB_LOCAL)
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
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c6dd0)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818c6dd0-ffffffff818c6ec5: mmc_mrq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e3880)
Location: drivers/mmc/core/core.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:mmc_start_request
```
**Symbols:**

```
ffffffff818e3880-ffffffff818e3975: mmc_mrq_prep (STB_LOCAL)
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

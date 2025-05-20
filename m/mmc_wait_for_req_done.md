# Function: <code>mmc_wait_for_req_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bf2d0)
Location: drivers/mmc/core/core.c:485
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
```
**Symbols:**

```
ffffffff816bf2d0-ffffffff816bf413: mmc_wait_for_req_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721ce0)
Location: drivers/mmc/core/core.c:486
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
```
**Symbols:**

```
ffffffff81721ce0-ffffffff81721e1f: mmc_wait_for_req_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81754be0)
Location: drivers/mmc/core/core.c:537
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81754be0-ffffffff81754d1f: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81772150)
Location: drivers/mmc/core/core.c:442
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81772150-ffffffff8177228b: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e82e0)
Location: drivers/mmc/core/core.c:447
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff817e82e0-ffffffff817e841b: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:399
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81834187-ffffffff818341df: mmc_wait_for_req_done.cold.36 (STB_LOCAL)
ffffffff81831730-ffffffff81831824: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:399
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81860117-ffffffff8186016f: mmc_wait_for_req_done.cold.38 (STB_LOCAL)
ffffffff8185d710-ffffffff8185d804: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818a3d36-ffffffff818a3d92: mmc_wait_for_req_done.cold (STB_LOCAL)
ffffffff818a1360-ffffffff818a1449: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818d6267-ffffffff818d62c3: mmc_wait_for_req_done.cold (STB_LOCAL)
ffffffff818d3650-ffffffff818d3739: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a5d50)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff819a5d50-ffffffff819a5e08: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8b00)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff819a8b00-ffffffff819a8bb8: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198d7d0)
Location: drivers/mmc/core/core.c:398
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff8198d7d0-ffffffff8198d888: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a38e20)
Location: drivers/mmc/core/core.c:398
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81a38e20-ffffffff81a38ed5: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba5ec0)
Location: drivers/mmc/core/core.c:398
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81ba5ec0-ffffffff81ba5f86: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d48200)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81d48200-ffffffff81d482c6: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db2b00)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81db2b00-ffffffff81db2bc4: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6ae90)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81e6ae90-ffffffff81e6af54: mmc_wait_for_req_done (STB_GLOBAL)
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
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2cb18)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffff800010b2cb18-ffff800010b2cc88: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c07e78)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
c0c07e78-c0c07fe4: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c258b0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
c000000000c258b0-c000000000c25aa8: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706b82)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffe000706b82-ffffffe000706cf0: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff81879c27-ffffffff81879c83: mmc_wait_for_req_done.cold (STB_LOCAL)
ffffffff81877010-ffffffff818770f9: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818cb0c7-ffffffff818cb123: mmc_wait_for_req_done.cold (STB_LOCAL)
ffffffff818c84b0-ffffffff818c8599: mmc_wait_for_req_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req_done(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
**Symbols:**

```
ffffffff818e7be7-ffffffff818e7c43: mmc_wait_for_req_done.cold (STB_LOCAL)
ffffffff818e4fd0-ffffffff818e50b9: mmc_wait_for_req_done (STB_GLOBAL)
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

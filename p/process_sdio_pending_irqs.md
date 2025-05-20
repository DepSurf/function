# Function: <code>process_sdio_pending_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff816cc290)
Location: drivers/mmc/core/sdio_irq.c:31
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff816cc290-ffffffff816cc44e: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8172f1e0)
Location: drivers/mmc/core/sdio_irq.c:31
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff8172f1e0-ffffffff8172f393: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817621d0)
Location: drivers/mmc/core/sdio_irq.c:31
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff817621d0-ffffffff81762383: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81780930)
Location: drivers/mmc/core/sdio_irq.c:34
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff81780930-ffffffff81780ae2: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817f6ef0)
Location: drivers/mmc/core/sdio_irq.c:34
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff817f6ef0-ffffffff817f70a8: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:34
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff81840400-ffffffff8184057a: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81840cb7-ffffffff81840d01: process_sdio_pending_irqs.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:34
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
**Symbols:**

```
ffffffff8186c3b0-ffffffff8186c52a: process_sdio_pending_irqs (STB_LOCAL)
ffffffff8186cc67-ffffffff8186ccb1: process_sdio_pending_irqs.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff818b0280-ffffffff818b0403: process_sdio_pending_irqs (STB_LOCAL)
ffffffff818b0b17-ffffffff818b0b63: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff818e2710-ffffffff818e28a7: process_sdio_pending_irqs (STB_LOCAL)
ffffffff818e2fc4-ffffffff818e3012: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff819b58f0-ffffffff819b59dc: process_sdio_pending_irqs (STB_LOCAL)
ffffffff819b60e4-ffffffff819b6130: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff819b7eb0-ffffffff819b7f9c: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81c2b2b6-ffffffff81c2b302: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff8199c5e0-ffffffff8199c777: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81c1d645-ffffffff81c1d693: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81a48fe0-ffffffff81a491a3: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81d2e7ab-ffffffff81d2e80e: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81bb72a0-ffffffff81bb7477: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81efac25-ffffffff81efac7f: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81d5bde0-ffffffff81d5c001: process_sdio_pending_irqs (STB_LOCAL)
ffffffff820a9b70-ffffffff820a9b85: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81dc6860-ffffffff81dc6a7d: process_sdio_pending_irqs (STB_LOCAL)
ffffffff8212af49-ffffffff8212af5e: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81e7f1a0-ffffffff81e7f3bd: process_sdio_pending_irqs (STB_LOCAL)
ffffffff8220cd06-ffffffff8220cd1b: process_sdio_pending_irqs.cold (STB_LOCAL)
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
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffff800010b3cf98)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffff800010b3cf98-ffff800010b3d180: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c0c17560)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
c0c17560-c0c17774: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c000000000c3a1c0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
c000000000c3a1c0-c000000000c3a47c: process_sdio_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffe00071422a)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffe00071422a-ffffffe0007143a0: process_sdio_pending_irqs (STB_LOCAL)
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
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff818860d0-ffffffff81886267: process_sdio_pending_irqs (STB_LOCAL)
ffffffff81886984-ffffffff818869d2: process_sdio_pending_irqs.cold (STB_LOCAL)
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
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff818d7570-ffffffff818d7707: process_sdio_pending_irqs (STB_LOCAL)
ffffffff818d7e24-ffffffff818d7e72: process_sdio_pending_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int process_sdio_pending_irqs(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff818f4090-ffffffff818f4227: process_sdio_pending_irqs (STB_LOCAL)
ffffffff818f4944-ffffffff818f4992: process_sdio_pending_irqs.cold (STB_LOCAL)
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

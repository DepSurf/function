# Function: <code>mmc_sdio_reinit_card</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host, bool powered_resume);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8183dc20)
Location: drivers/mmc/core/sdio.c:816
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8183dc20-ffffffff8183dc82: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host, bool powered_resume);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81869bd0)
Location: drivers/mmc/core/sdio.c:816
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81869bd0-ffffffff81869c32: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818adaa0)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818adaa0-ffffffff818adafb: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818dff00)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818dff00-ffffffff818dff5b: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b2f60)
Location: drivers/mmc/core/sdio.c:850
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff819b2f60-ffffffff819b2fc2: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b54b0)
Location: drivers/mmc/core/sdio.c:894
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff819b54b0-ffffffff819b5512: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81999a40)
Location: drivers/mmc/core/sdio.c:894
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81999a40-ffffffff81999aa2: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81a461e0)
Location: drivers/mmc/core/sdio.c:896
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81a461e0-ffffffff81a46242: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81bb3f10)
Location: drivers/mmc/core/sdio.c:898
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81bb3f10-ffffffff81bb3f79: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81d58530)
Location: drivers/mmc/core/sdio.c:912
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81d58530-ffffffff81d58599: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81dc2ec0)
Location: drivers/mmc/core/sdio.c:912
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81dc2ec0-ffffffff81dc2f29: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81e7b780)
Location: drivers/mmc/core/sdio.c:912
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81e7b780-ffffffff81e7b7e9: mmc_sdio_reinit_card (STB_LOCAL)
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
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b3a058)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffff800010b3a058-ffff800010b3a0c0: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c0c14a98)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c0c14a98-c0c14af8: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c000000000c36800)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c000000000c36800-c000000000c368a0: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffe000711c10)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffe000711c10-ffffffe000711c78: mmc_sdio_reinit_card (STB_LOCAL)
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
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818838c0)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818838c0-ffffffff8188391b: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818d4d60)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818d4d60-ffffffff818d4dbb: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mmc_sdio_reinit_card(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818f1880)
Location: drivers/mmc/core/sdio.c:817
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff818f1880-ffffffff818f18db: mmc_sdio_reinit_card (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool powered_resume</code>
</li>
</ul>
</details>
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

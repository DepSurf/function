# Function: <code>sdio_run_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff816cc450)
Location: drivers/mmc/core/sdio_irq.c:92
Inline: False
```
**Symbols:**

```
ffffffff816cc450-ffffffff816cc47e: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8172f3a0)
Location: drivers/mmc/core/sdio_irq.c:92
Inline: False
```
**Symbols:**

```
ffffffff8172f3a0-ffffffff8172f3ce: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81762390)
Location: drivers/mmc/core/sdio_irq.c:92
Inline: False
```
**Symbols:**

```
ffffffff81762390-ffffffff817623be: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81780af0)
Location: drivers/mmc/core/sdio_irq.c:95
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81780af0-ffffffff81780b48: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817f70b0)
Location: drivers/mmc/core/sdio_irq.c:95
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff817f70b0-ffffffff817f710d: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81840580)
Location: drivers/mmc/core/sdio_irq.c:95
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff81840580-ffffffff818405dd: sdio_run_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sdio_run_irqs(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8186c530)
Location: drivers/mmc/core/sdio_irq.c:95
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
**Symbols:**

```
ffffffff8186c530-ffffffff8186c58d: sdio_run_irqs (STB_GLOBAL)
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
In drivers/mmc/core/sdio_irq.c (ffffffff818b0ac6)
Location: drivers/mmc/core/sdio_irq.c:95
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff818e2f76)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff819b6096)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff819b8616)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff8199cd46)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff81a49738)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff81bb7a48)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff81d5c668)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81dc70c8)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81e7fa08)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffff800010b3d80c)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (c0c17e40)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (c000000000c3ad70)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffe0007148ce)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff81886936)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818d7dd6)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
In drivers/mmc/core/sdio_irq.c (ffffffff818f48f6)
Location: drivers/mmc/core/sdio_irq.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
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
</ul>

# Function: <code>sdio_get_pending_irqs</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818e279f)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_get_pending_irqs(struct mmc_host *host, u8 *pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b5800)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff819b5800-ffffffff819b58e8: sdio_get_pending_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_get_pending_irqs(struct mmc_host *host, u8 *pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b7dc0)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff819b7dc0-ffffffff819b7ea8: sdio_get_pending_irqs (STB_LOCAL)
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
In drivers/mmc/core/sdio_irq.c (ffffffff8199c66f)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff81a4907c)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff81bb7352)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff81d5be92)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff81dc6910)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff81e7f250)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffff800010b3d028)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (c0c175f4)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (c000000000c3a22c)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffe00071426e)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff8188615f)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff818d75ff)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
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
In drivers/mmc/core/sdio_irq.c (ffffffff818f411f)
Location: drivers/mmc/core/sdio_irq.c:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>

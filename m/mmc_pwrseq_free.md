# Function: <code>mmc_pwrseq_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:55
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:55
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
void mmc_pwrseq_free(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/pwrseq.c (ffff800010b3e580)
Location: drivers/mmc/core/pwrseq.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_free_host
```
**Symbols:**

```
ffff800010b3e580-ffff800010b3e5b8: mmc_pwrseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_pwrseq_free(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/pwrseq.c (c0c18a94)
Location: drivers/mmc/core/pwrseq.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_free_host
```
**Symbols:**

```
c0c18a94-c0c18acc: mmc_pwrseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_pwrseq_free(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/pwrseq.c (c000000000c3c0d0)
Location: drivers/mmc/core/pwrseq.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_free_host
```
**Symbols:**

```
c000000000c3c0d0-c000000000c3c128: mmc_pwrseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_pwrseq_free(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/pwrseq.c (ffffffe000715484)
Location: drivers/mmc/core/pwrseq.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_free_host
```
**Symbols:**

```
ffffffe000715484-ffffffe0007154b8: mmc_pwrseq_free (STB_GLOBAL)
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
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
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/pwrseq.h:54
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

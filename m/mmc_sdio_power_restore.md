# Function: <code>mmc_sdio_power_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff816c9820)
Location: drivers/mmc/core/sdio.c:971
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff816c9820-ffffffff816c98f1: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8172c7e0)
Location: drivers/mmc/core/sdio.c:969
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff8172c7e0-ffffffff8172c8b1: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8175f990)
Location: drivers/mmc/core/sdio.c:960
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff8175f990-ffffffff8175fa46: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8177e1a0)
Location: drivers/mmc/core/sdio.c:978
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff8177e1a0-ffffffff8177e256: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff817f4730)
Location: drivers/mmc/core/sdio.c:978
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff817f4730-ffffffff817f47ee: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8183dce0)
Location: drivers/mmc/core/sdio.c:998
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff8183dce0-ffffffff8183dd59: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_sdio_power_restore(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81869c90)
Location: drivers/mmc/core/sdio.c:998
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
```
**Symbols:**

```
ffffffff81869c90-ffffffff81869d09: mmc_sdio_power_restore (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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

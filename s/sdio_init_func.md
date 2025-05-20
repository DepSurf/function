# Function: <code>sdio_init_func</code>

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
In drivers/mmc/core/sdio.c (ffffffff816c9dfd)
Location: drivers/mmc/core/sdio.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff8172cdbb)
Location: drivers/mmc/core/sdio.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff8175fd69)
Location: drivers/mmc/core/sdio.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff8177e66d)
Location: drivers/mmc/core/sdio.c:64
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff817f4c0d)
Location: drivers/mmc/core/sdio.c:64
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff8183e09e)
Location: drivers/mmc/core/sdio.c:64
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff8186a04e)
Location: drivers/mmc/core/sdio.c:64
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff818adecf)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff818e037f)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_init_func(struct mmc_card *card, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b22b0)
Location: drivers/mmc/core/sdio.c:78
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819b22b0-ffffffff819b2366: sdio_init_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_init_func(struct mmc_card *card, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b47f0)
Location: drivers/mmc/core/sdio.c:102
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819b47f0-ffffffff819b48a6: sdio_init_func (STB_LOCAL)
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
In drivers/mmc/core/sdio.c (ffffffff8199a04b)
Location: drivers/mmc/core/sdio.c:102
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81a468ce)
Location: drivers/mmc/core/sdio.c:102
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81bb4688)
Location: drivers/mmc/core/sdio.c:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81d58d30)
Location: drivers/mmc/core/sdio.c:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81dc36b6)
Location: drivers/mmc/core/sdio.c:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81e7bf96)
Location: drivers/mmc/core/sdio.c:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffff800010b3a57c)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (c0c14f54)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (c000000000c36dc0)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffe000711fc6)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff81883d3f)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff818d51df)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/mmc/core/sdio.c (ffffffff818f1cff)
Location: drivers/mmc/core/sdio.c:60
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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

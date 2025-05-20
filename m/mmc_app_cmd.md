# Function: <code>mmc_app_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff816c8010)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
```
**Symbols:**

```
ffffffff816c8010-ffffffff816c80c4: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8172afd0)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff8172afd0-ffffffff8172b07f: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8175e090)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff8175e090-ffffffff8175e14c: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8177c7c0)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff8177c7c0-ffffffff8177c86d: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff817f2d40)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff817f2d40-ffffffff817f2ded: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8183c190)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff8183c190-ffffffff8183c241: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81868120)
Location: drivers/mmc/core/sd_ops.c:25
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81868120-ffffffff818681d1: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd_ops.c (0)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff818ac895-ffffffff818ac8ad: mmc_app_cmd.cold (STB_LOCAL)
ffffffff818ac080-ffffffff818ac12d: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818de4c0)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff818de4c0-ffffffff818de572: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b12e0)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff819b12e0-ffffffff819b1390: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b3540)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff819b3540-ffffffff819b35f0: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81997d20)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81997d20-ffffffff81997dcf: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81a444e0)
Location: drivers/mmc/core/sd_ops.c:22
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81a444e0-ffffffff81a4458f: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81bb1fc0)
Location: drivers/mmc/core/sd_ops.c:22
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81bb1fc0-ffffffff81bb207b: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81d56240)
Location: drivers/mmc/core/sd_ops.c:22
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81d56240-ffffffff81d562fb: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81dc0bb0)
Location: drivers/mmc/core/sd_ops.c:22
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81dc0bb0-ffffffff81dc0c6b: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81e79440)
Location: drivers/mmc/core/sd_ops.c:22
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81e79440-ffffffff81e794fb: mmc_app_cmd (STB_GLOBAL)
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
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffff800010b38580)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff800010b38580-ffff800010b38664: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c0c12ef0)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0c12ef0-c0c12ff0: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c000000000c34320)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
c000000000c34320-c000000000c3445c: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffe0007103fa)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe0007103fa-ffffffe0007104ac: mmc_app_cmd (STB_GLOBAL)
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
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81881e80)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff81881e80-ffffffff81881f32: mmc_app_cmd (STB_GLOBAL)
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
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818d3320)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff818d3320-ffffffff818d33d2: mmc_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_app_cmd(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818efe40)
Location: drivers/mmc/core/sd_ops.c:21
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
```
**Symbols:**

```
ffffffff818efe40-ffffffff818efef2: mmc_app_cmd (STB_GLOBAL)
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

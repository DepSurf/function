# Function: <code>mmc_wait_for_app_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff816c80d0)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
**Symbols:**

```
ffffffff816c80d0-ffffffff816c81b9: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8172b080)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff8172b080-ffffffff8172b169: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8175e150)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff8175e150-ffffffff8175e23b: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8177c870)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff8177c870-ffffffff8177c982: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff817f2df0)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff817f2df0-ffffffff817f2f08: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff8183c250)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff8183c250-ffffffff8183c368: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818681e0)
Location: drivers/mmc/core/sd_ops.c:68
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff818681e0-ffffffff818682f8: mmc_wait_for_app_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818ac130)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff818ac130-ffffffff818ac22a: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818de580)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff818de580-ffffffff818de67a: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b1390)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff819b1390-ffffffff819b149d: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff819b36b0)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff819b36b0-ffffffff819b37bd: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81997e90)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81997e90-ffffffff81997f9d: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81a44650)
Location: drivers/mmc/core/sd_ops.c:52
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81a44650-ffffffff81a4475d: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81bb2140)
Location: drivers/mmc/core/sd_ops.c:52
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81bb2140-ffffffff81bb225f: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81d563e0)
Location: drivers/mmc/core/sd_ops.c:52
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81d563e0-ffffffff81d564ff: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81dc0d50)
Location: drivers/mmc/core/sd_ops.c:52
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81dc0d50-ffffffff81dc0e6f: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81e795e0)
Location: drivers/mmc/core/sd_ops.c:52
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81e795e0-ffffffff81e796ff: mmc_wait_for_app_cmd (STB_LOCAL)
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
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffff800010b38668)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffff800010b38668-ffff800010b3876c: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c0c12ff0)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
c0c12ff0-c0c130f8: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (c000000000c34460)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
c000000000c34460-c000000000c345a4: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffe0007104ac)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffe0007104ac-ffffffe000710568: mmc_wait_for_app_cmd (STB_LOCAL)
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
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff81881f40)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff81881f40-ffffffff8188203a: mmc_wait_for_app_cmd (STB_LOCAL)
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
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818d33e0)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff818d33e0-ffffffff818d34da: mmc_wait_for_app_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_wait_for_app_cmd(struct mmc_host *host, struct mmc_card *card, struct mmc_command *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd_ops.c (ffffffff818eff00)
Location: drivers/mmc/core/sd_ops.c:51
Inline: False
Direct callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_set_bus_width
```
**Symbols:**

```
ffffffff818eff00-ffffffff818efffa: mmc_wait_for_app_cmd (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int retries</code>
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

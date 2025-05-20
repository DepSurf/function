# Function: <code>mbox_chan_txdone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff816eb740)
Location: drivers/mailbox/mailbox.c:169
Inline: True
```
**Symbols:**

```
ffffffff816eb740-ffffffff816eb76a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81750220)
Location: drivers/mailbox/mailbox.c:169
Inline: True
```
**Symbols:**

```
ffffffff81750220-ffffffff8175024a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8177bde0)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8177bde0-ffffffff8177be0a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8179a8a0)
Location: drivers/mailbox/mailbox.c:171
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8179a8a0-ffffffff8179a8ca: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81810c60)
Location: drivers/mailbox/mailbox.c:171
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81810c60-ffffffff81810c8a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8185ab00)
Location: drivers/mailbox/mailbox.c:171
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8185ab00-ffffffff8185ab2a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81879f00)
Location: drivers/mailbox/mailbox.c:171
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81879f00-ffffffff81879f2a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818bf885)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818bf885-ffffffff818bf89c: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff818bf4d0-ffffffff818bf4ea: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818f23bf)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818f23bf-ffffffff818f23d6: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff818f2020-ffffffff818f203a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c7c58)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff819c7c58-ffffffff819c7c6f: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff819c7b00-ffffffff819c7b1a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81c2d991)
Location: drivers/mailbox/mailbox.c:170
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81c2d991-ffffffff81c2d9a8: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff819c7a50-ffffffff819c7a6a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81c1fbf7)
Location: drivers/mailbox/mailbox.c:170
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81c1fbf7-ffffffff81c1fc0e: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff819ac990-ffffffff819ac9aa: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81d31545)
Location: drivers/mailbox/mailbox.c:170
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81d31545-ffffffff81d3155c: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff81a5aea0-ffffffff81a5aeba: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81efd99f)
Location: drivers/mailbox/mailbox.c:176
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81efd99f-ffffffff81efd9b6: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff81bca6f0-ffffffff81bca714: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81d73d70)
Location: drivers/mailbox/mailbox.c:176
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81d73d70-ffffffff81d73dae: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81de1a10)
Location: drivers/mailbox/mailbox.c:176
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81de1a10-ffffffff81de1a4e: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81e979d0)
Location: drivers/mailbox/mailbox.c:177
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81e979d0-ffffffff81e97a0e: mbox_chan_txdone (STB_GLOBAL)
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
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffff800010b7a3a8)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffff800010b7a3a8-ffff800010b7a3fc: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c0c5fb24)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_flush
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
```
**Symbols:**

```
c0c5fb24-c0c5fb64: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c000000000c59330)
Location: drivers/mailbox/mailbox.c:168
Inline: True
```
**Symbols:**

```
c000000000c59330-c000000000c59384: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffe00072bf2c)
Location: drivers/mailbox/mailbox.c:168
Inline: True
```
**Symbols:**

```
ffffffe00072bf2c-ffffffe00072bf7a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818936ef)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818936ef-ffffffff81893706: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff81893350-ffffffff8189336a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8184bbef)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8184bbef-ffffffff8184bc06: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff8184b850-ffffffff8184b86a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818e71ef)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818e71ef-ffffffff818e7206: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff818e6e50-ffffffff818e6e6a: mbox_chan_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_chan_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81903e6f)
Location: drivers/mailbox/mailbox.c:168
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81903e6f-ffffffff81903e86: mbox_chan_txdone.cold (STB_LOCAL)
ffffffff81903ad0-ffffffff81903aea: mbox_chan_txdone (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

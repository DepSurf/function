# Function: <code>spi_transfer_one_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_master *master, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e73b0)
Location: drivers/spi/spi.c:918
Inline: False
```
**Symbols:**

```
ffffffff815e73b0-ffffffff815e776f: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_master *master, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645ce0)
Location: drivers/spi/spi.c:957
Inline: False
```
**Symbols:**

```
ffffffff81645ce0-ffffffff816460ac: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_master *master, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81676ae0)
Location: drivers/spi/spi.c:976
Inline: False
```
**Symbols:**

```
ffffffff81676ae0-ffffffff81676ed5: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168b1d0)
Location: drivers/spi/spi.c:1002
Inline: False
```
**Symbols:**

```
ffffffff8168b1d0-ffffffff8168b5e6: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f4b50)
Location: drivers/spi/spi.c:1006
Inline: False
```
**Symbols:**

```
ffffffff816f4b50-ffffffff816f4f74: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81732c20)
Location: drivers/spi/spi.c:1003
Inline: False
```
**Symbols:**

```
ffffffff81732c20-ffffffff8173303c: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81755640)
Location: drivers/spi/spi.c:1081
Inline: False
```
**Symbols:**

```
ffffffff81755640-ffffffff81755ab1: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1154
Inline: False
```
**Symbols:**

```
ffffffff81791730-ffffffff81791bdd: spi_transfer_one_message (STB_LOCAL)
ffffffff81792a5f-ffffffff81792a98: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffff817b5330-ffffffff817b57dd: spi_transfer_one_message (STB_LOCAL)
ffffffff817b65c1-ffffffff817b65fa: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1221
Inline: False
```
**Symbols:**

```
ffffffff8187c280-ffffffff8187c763: spi_transfer_one_message (STB_LOCAL)
ffffffff8187d497-ffffffff8187d4ca: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1245
Inline: False
```
**Symbols:**

```
ffffffff8188a520-ffffffff8188aa3e: spi_transfer_one_message (STB_LOCAL)
ffffffff81c18ebe-ffffffff81c18ef1: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1257
Inline: False
```
**Symbols:**

```
ffffffff8186cf00-ffffffff8186d3d8: spi_transfer_one_message (STB_LOCAL)
ffffffff81c0acec-ffffffff81c0ad1f: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1336
Inline: False
```
**Symbols:**

```
ffffffff818fcea0-ffffffff818fd3b1: spi_transfer_one_message (STB_LOCAL)
ffffffff81d0feb6-ffffffff81d0ff95: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81a4e4a0-ffffffff81a4e9f0: spi_transfer_one_message (STB_LOCAL)
ffffffff81edabb5-ffffffff81edac93: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1494
Inline: False
```
**Symbols:**

```
ffffffff81bd5dd0-ffffffff81bd6382: spi_transfer_one_message (STB_LOCAL)
ffffffff8209d192-ffffffff8209d229: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1501
Inline: False
```
**Symbols:**

```
ffffffff81c2cb90-ffffffff81c2d1e6: spi_transfer_one_message (STB_LOCAL)
ffffffff8211e07e-ffffffff8211e115: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1574
Inline: False
```
**Symbols:**

```
ffffffff81cdf6c0-ffffffff81cdfbed: spi_transfer_one_message (STB_LOCAL)
ffffffff821ff61c-ffffffff821ff692: spi_transfer_one_message.cold (STB_LOCAL)
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
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c8b18)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffff8000109c8b18-ffff8000109c90bc: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab2684)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
c0ab2684-c0ab2b38: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8a520)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
c000000000a8a520-c000000000a8aba0: spi_transfer_one_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000618e32)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffe000618e32-ffffffe0006192d4: spi_transfer_one_message (STB_LOCAL)
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
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81779e10-ffffffff8177a2bd: spi_transfer_one_message (STB_LOCAL)
ffffffff8177b0a1-ffffffff8177b0da: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81759bc0-ffffffff8175a06d: spi_transfer_one_message (STB_LOCAL)
ffffffff8175ae51-ffffffff8175ae8a: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffff817aa1b0-ffffffff817aa65d: spi_transfer_one_message (STB_LOCAL)
ffffffff817ab441-ffffffff817ab47a: spi_transfer_one_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int spi_transfer_one_message(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1155
Inline: False
```
**Symbols:**

```
ffffffff817c4050-ffffffff817c452f: spi_transfer_one_message (STB_LOCAL)
ffffffff817c53d1-ffffffff817c540a: spi_transfer_one_message.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct spi_controller *ctlr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct spi_master *master</code>
</li>
</ul>
</details>
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

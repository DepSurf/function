# Function: <code>spi_res_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void spi_res_release(struct spi_master *master, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81644560)
Location: drivers/spi/spi.c:2156
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81644560-ffffffff816445ed: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void spi_res_release(struct spi_master *master, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81675630)
Location: drivers/spi/spi.c:2183
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81675630-ffffffff816756bd: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81689d60)
Location: drivers/spi/spi.c:2347
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81689d60-ffffffff81689df3: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f3620)
Location: drivers/spi/spi.c:2417
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff816f3620-ffffffff816f36b6: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817300d0)
Location: drivers/spi/spi.c:2467
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817300d0-ffffffff81730160: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817524a0)
Location: drivers/spi/spi.c:2533
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817524a0-ffffffff81752530: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178dfb0)
Location: drivers/spi/spi.c:2741
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8178dfb0-ffffffff8178e04d: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b1bc0)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817b1bc0-ffffffff817b1c5d: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81877950)
Location: drivers/spi/spi.c:2951
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
**Symbols:**

```
ffffffff81877950-ffffffff818779ed: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886260)
Location: drivers/spi/spi.c:3040
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
**Symbols:**

```
ffffffff81886260-ffffffff818862fd: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81868ad0)
Location: drivers/spi/spi.c:3047
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
**Symbols:**

```
ffffffff81868ad0-ffffffff81868b6d: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818f85d0)
Location: drivers/spi/spi.c:3176
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
**Symbols:**

```
ffffffff818f85d0-ffffffff818f866d: spi_res_release (STB_GLOBAL)
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
In drivers/spi/spi.c (ffffffff81a4cbc8)
Location: drivers/spi/spi.c:887
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81bd4de6)
Location: drivers/spi/spi.c:949
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81c2bcb3)
Location: drivers/spi/spi.c:950
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81cde5d3)
Location: drivers/spi/spi.c:989
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c2010)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffff8000109c2010-ffff8000109c20b8: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaeee0)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c0aaeee0-c0aaef68: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a85610)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c000000000a85610-c000000000a8572c: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000615b9e)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffe000615b9e-ffffffe000615c22: spi_res_release (STB_GLOBAL)
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
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817766a0)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817766a0-ffffffff8177673d: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81756450)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81756450-ffffffff817564ed: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a6a40)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817a6a40-ffffffff817a6add: spi_res_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void spi_res_release(struct spi_controller *ctlr, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c08c0)
Location: drivers/spi/spi.c:2745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817c08c0-ffffffff817c095d: spi_res_release (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

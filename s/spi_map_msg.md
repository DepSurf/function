# Function: <code>spi_map_msg</code>

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
In drivers/spi/spi.c (ffffffff815e7c6a)
Location: drivers/spi/spi.c:861
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff8164636c)
Location: drivers/spi/spi.c:900
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff8167745c)
Location: drivers/spi/spi.c:919
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff8168b981)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff816f52f4)
Location: drivers/spi/spi.c:949
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff81733138)
Location: drivers/spi/spi.c:946
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff81755bb8)
Location: drivers/spi/spi.c:988
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff81791ce8)
Location: drivers/spi/spi.c:1005
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff817b58d1)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187bce0)
Location: drivers/spi/spi.c:1032
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff8187bce0-ffffffff8187bf7c: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188ae10)
Location: drivers/spi/spi.c:1052
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff8188ae10-ffffffff8188b0b6: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186d780)
Location: drivers/spi/spi.c:1064
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff8186d780-ffffffff8186da26: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fd770)
Location: drivers/spi/spi.c:1128
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff818fd770-ffffffff818fda55: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4edf0)
Location: drivers/spi/spi.c:1172
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81a4edf0-ffffffff81a4f0c5: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd1980)
Location: drivers/spi/spi.c:1287
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
**Symbols:**

```
ffffffff81bd1980-ffffffff81bd1c76: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2aaf0)
Location: drivers/spi/spi.c:1287
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
**Symbols:**

```
ffffffff81c2aaf0-ffffffff81c2ade6: spi_map_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spi_map_msg(struct spi_controller *ctlr, struct spi_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdd340)
Location: drivers/spi/spi.c:1357
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
**Symbols:**

```
ffffffff81cdd340-ffffffff81cdd636: spi_map_msg (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c91ec)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (c0ab2c20)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (c000000000a8adc4)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffe00061939a)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff8177a3b1)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175a161)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817aa751)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/spi/spi.c (ffffffff817c4621)
Location: drivers/spi/spi.c:1006
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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

# Function: <code>__spi_pump_messages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_master *master, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e79f0)
Location: drivers/spi/spi.c:1042
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_pump_messages
  - drivers/spi/spi.c:__spi_sync
```
**Symbols:**

```
ffffffff815e79f0-ffffffff815e7ff2: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_master *master, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816460b0)
Location: drivers/spi/spi.c:1087
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff816460b0-ffffffff81646703: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_master *master, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816771a0)
Location: drivers/spi/spi.c:1112
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff816771a0-ffffffff816777f3: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168b890)
Location: drivers/spi/spi.c:1138
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8168b890-ffffffff8168bec8: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f5200)
Location: drivers/spi/spi.c:1142
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff816f5200-ffffffff816f5853: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81733040)
Location: drivers/spi/spi.c:1139
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81733040-ffffffff817336d2: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81755ac0)
Location: drivers/spi/spi.c:1199
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81755ac0-ffffffff81756150: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1266
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81791be0-ffffffff817921fc: __spi_pump_messages (STB_LOCAL)
ffffffff81792a98-ffffffff81792b3b: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff817b57e0-ffffffff817b5dcd: __spi_pump_messages (STB_LOCAL)
ffffffff817b65fa-ffffffff817b668c: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1340
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8187c770-ffffffff8187cb92: __spi_pump_messages (STB_LOCAL)
ffffffff8187d4ca-ffffffff8187d55e: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1381
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8188b0c0-ffffffff8188b541: __spi_pump_messages (STB_LOCAL)
ffffffff81c18f09-ffffffff81c18f9d: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1393
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8186da30-ffffffff8186debc: __spi_pump_messages (STB_LOCAL)
ffffffff81c0ad37-ffffffff81c0adcb: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1472
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff818fda60-ffffffff818fdf59: __spi_pump_messages (STB_LOCAL)
ffffffff81d0ffad-ffffffff81d10107: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1515
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81a4f0d0-ffffffff81a4f6b4: __spi_pump_messages (STB_LOCAL)
ffffffff81edacab-ffffffff81edae1a: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1747
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81bd6bf0-ffffffff81bd6f53: __spi_pump_messages (STB_LOCAL)
ffffffff8209d2bf-ffffffff8209d33c: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1754
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81c2d620-ffffffff81c2d983: __spi_pump_messages (STB_LOCAL)
ffffffff8211e17c-ffffffff8211e1f9: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1831
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff81ce0010-ffffffff81ce0373: __spi_pump_messages (STB_LOCAL)
ffffffff821ff6f9-ffffffff821ff776: __spi_pump_messages.cold (STB_LOCAL)
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
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c90c0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffff8000109c90c0-ffff8000109c9758: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab2b38)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
c0ab2b38-c0ab321c: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8aba0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
c000000000a8aba0-c000000000a8b3a8: __spi_pump_messages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe0006192d4)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffe0006192d4-ffffffe000619838: __spi_pump_messages (STB_LOCAL)
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
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8177a2c0-ffffffff8177a8ad: __spi_pump_messages (STB_LOCAL)
ffffffff8177b0da-ffffffff8177b16c: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff8175a070-ffffffff8175a65d: __spi_pump_messages (STB_LOCAL)
ffffffff8175ae8a-ffffffff8175af1c: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff817aa660-ffffffff817aac4d: __spi_pump_messages (STB_LOCAL)
ffffffff817ab47a-ffffffff817ab50c: __spi_pump_messages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __spi_pump_messages(struct spi_controller *ctlr, bool in_kthread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1267
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_flush_queue
  - drivers/spi/spi.c:spi_pump_messages
```
**Symbols:**

```
ffffffff817c4530-ffffffff817c4bc4: __spi_pump_messages (STB_LOCAL)
ffffffff817c540a-ffffffff817c549c: __spi_pump_messages.cold (STB_LOCAL)
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

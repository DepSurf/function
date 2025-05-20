# Function: <code>xennet_tx_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fab00)
Location: drivers/net/xen-netfront.c:1218
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff815fab00-ffffffff815fab42: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165a9e0)
Location: drivers/net/xen-netfront.c:1209
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff8165a9e0-ffffffff8165aa22: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688740)
Location: drivers/net/xen-netfront.c:1212
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff81688740-ffffffff81688782: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169def0)
Location: drivers/net/xen-netfront.c:1211
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff8169def0-ffffffff8169df32: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81709090)
Location: drivers/net/xen-netfront.c:1213
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff81709090-ffffffff817090d2: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81747bd0)
Location: drivers/net/xen-netfront.c:1222
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff81747bd0-ffffffff81747c12: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8176bcc0)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff8176bcc0-ffffffff8176bd02: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817a9ab0)
Location: drivers/net/xen-netfront.c:1220
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff817a9ab0-ffffffff817a9af4: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817cd520)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff817cd520-ffffffff817cd564: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8189a388)
Location: drivers/net/xen-netfront.c:1223
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff8189a600-ffffffff8189a657: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a8358)
Location: drivers/net/xen-netfront.c:1376
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff818a85e0-ffffffff818a8637: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8188ac8c)
Location: drivers/net/xen-netfront.c:1374
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff81889750-ffffffff81889794: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191c260)
Location: drivers/net/xen-netfront.c:1485
Inline: False
```
**Symbols:**

```
ffffffff8191c260-ffffffff8191c2c2: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a717f0)
Location: drivers/net/xen-netfront.c:1522
Inline: False
```
**Symbols:**

```
ffffffff81a717f0-ffffffff81a71857: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c07430)
Location: drivers/net/xen-netfront.c:1522
Inline: False
```
**Symbols:**

```
ffffffff81c07430-ffffffff81c07497: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6cb30)
Location: drivers/net/xen-netfront.c:1522
Inline: False
```
**Symbols:**

```
ffffffff81c6cb30-ffffffff81c6cb97: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d21480)
Location: drivers/net/xen-netfront.c:1523
Inline: False
```
**Symbols:**

```
ffffffff81d21480-ffffffff81d214e7: xennet_tx_interrupt (STB_LOCAL)
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
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a08498)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffff800010a08498-ffff800010a08540: xennet_tx_interrupt (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81792140)
Location: drivers/net/xen-netfront.c:1253
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff81792140-ffffffff81792184: xennet_tx_interrupt (STB_LOCAL)
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
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c23a0)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff817c23a0-ffffffff817c23e4: xennet_tx_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t xennet_tx_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817dc660)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
```
**Symbols:**

```
ffffffff817dc660-ffffffff817dc6a4: xennet_tx_interrupt (STB_LOCAL)
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

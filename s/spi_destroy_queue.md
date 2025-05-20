# Function: <code>spi_destroy_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e6ed0)
Location: drivers/spi/spi.c:1333
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff815e6ed0-ffffffff815e6f21: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816454b0)
Location: drivers/spi/spi.c:1389
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff816454b0-ffffffff81645502: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816765b0)
Location: drivers/spi/spi.c:1414
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff816765b0-ffffffff81676602: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168acc0)
Location: drivers/spi/spi.c:1438
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8168acc0-ffffffff8168ad12: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f4580)
Location: drivers/spi/spi.c:1442
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff816f4580-ffffffff816f45d2: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81730fe0)
Location: drivers/spi/spi.c:1440
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81730fe0-ffffffff81731032: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817539d0)
Location: drivers/spi/spi.c:1500
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817539d0-ffffffff81753a22: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1591
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8178e840-ffffffff8178e883: spi_destroy_queue (STB_LOCAL)
ffffffff8179270f-ffffffff81792723: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817b2400-ffffffff817b2443: spi_destroy_queue (STB_LOCAL)
ffffffff817b62b1-ffffffff817b62c5: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187987e)
Location: drivers/spi/spi.c:1778
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81878340-ffffffff81878383: spi_destroy_queue (STB_LOCAL)
ffffffff8187d181-ffffffff8187d195: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81887fbd)
Location: drivers/spi/spi.c:1821
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
Direct callers:
  - drivers/spi/spi.c:spi_controller_initialize_queue
```
**Symbols:**

```
ffffffff81886a90-ffffffff81886ac6: spi_destroy_queue (STB_LOCAL)
ffffffff81c18b7c-ffffffff81c18b90: spi_destroy_queue.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8186a807)
Location: drivers/spi/spi.c:1833
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff818faba0)
Location: drivers/spi/spi.c:1912
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff81a4c6dc)
Location: drivers/spi/spi.c:1956
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff81bd56c8)
Location: drivers/spi/spi.c:2116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
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
In drivers/spi/spi.c (ffffffff81c2c3f8)
Location: drivers/spi/spi.c:2123
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
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
In drivers/spi/spi.c (ffffffff81cded18)
Location: drivers/spi/spi.c:2196
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
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
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c7698)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffff8000109c7698-ffff8000109c76f4: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf91c)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c0aaf91c-c0aaf96c: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a86300)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000a86300-c000000000a86380: spi_destroy_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe00061640e)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe00061640e-ffffffe00061646e: spi_destroy_queue (STB_LOCAL)
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
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81776ee0-ffffffff81776f23: spi_destroy_queue (STB_LOCAL)
ffffffff8177ad91-ffffffff8177ada5: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81756c90-ffffffff81756cd3: spi_destroy_queue (STB_LOCAL)
ffffffff8175ab41-ffffffff8175ab55: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817a7280-ffffffff817a72c3: spi_destroy_queue (STB_LOCAL)
ffffffff817ab131-ffffffff817ab145: spi_destroy_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int spi_destroy_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1593
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817c1100-ffffffff817c1143: spi_destroy_queue (STB_LOCAL)
ffffffff817c50c1-ffffffff817c50d5: spi_destroy_queue.cold (STB_LOCAL)
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

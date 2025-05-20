# Function: <code>spi_start_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int spi_start_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e68b0)
Location: drivers/spi/spi.c:1278
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff815e68b0-ffffffff815e692c: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spi_start_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81644c80)
Location: drivers/spi/spi.c:1334
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff81644c80-ffffffff81644cf3: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int spi_start_queue(struct spi_master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81675d50)
Location: drivers/spi/spi.c:1359
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_master
```
**Symbols:**

```
ffffffff81675d50-ffffffff81675dc3: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168a450)
Location: drivers/spi/spi.c:1384
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8168a450-ffffffff8168a4c3: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f3c60)
Location: drivers/spi/spi.c:1388
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff816f3c60-ffffffff816f3cd3: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817306a0)
Location: drivers/spi/spi.c:1386
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817306a0-ffffffff81730713: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81752d60)
Location: drivers/spi/spi.c:1446
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81752d60-ffffffff81752dd3: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178e5e0)
Location: drivers/spi/spi.c:1537
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8178e5e0-ffffffff8178e650: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b21a0)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817b21a0-ffffffff817b2210: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187b04d)
Location: drivers/spi/spi.c:1724
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886b85)
Location: drivers/spi/spi.c:1767
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_controller_initialize_queue
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
In drivers/spi/spi.c (ffffffff8186c6f9)
Location: drivers/spi/spi.c:1779
Inline: True
Inline callers:
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
In drivers/spi/spi.c (ffffffff818fc59b)
Location: drivers/spi/spi.c:1858
Inline: True
Inline callers:
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
In drivers/spi/spi.c (ffffffff81a4dc3a)
Location: drivers/spi/spi.c:1902
Inline: True
Inline callers:
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
In drivers/spi/spi.c (ffffffff81bd5838)
Location: drivers/spi/spi.c:2062
Inline: True
Inline callers:
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
In drivers/spi/spi.c (ffffffff81c2c563)
Location: drivers/spi/spi.c:2069
Inline: True
Inline callers:
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
In drivers/spi/spi.c (ffffffff81cde3e5)
Location: drivers/spi/spi.c:2146
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_controller_resume
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
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c6fd0)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffff8000109c6fd0-ffff8000109c70b0: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf57c)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c0aaf57c-c0aaf5f0: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a85f50)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000a85f50-c000000000a85ff0: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe0006161a4)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe0006161a4-ffffffe00061621a: spi_start_queue (STB_LOCAL)
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
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81776c80)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81776c80-ffffffff81776cf0: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81756a30)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81756a30-ffffffff81756aa0: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a7020)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817a7020-ffffffff817a7090: spi_start_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_start_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c0ea0)
Location: drivers/spi/spi.c:1539
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817c0ea0-ffffffff817c0f10: spi_start_queue (STB_LOCAL)
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

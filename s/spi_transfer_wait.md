# Function: <code>spi_transfer_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817557b6)
Location: drivers/spi/spi.c:1038
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff817919cd)
Location: drivers/spi/spi.c:1057
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff817b55cd)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff8187c574)
Location: drivers/spi/spi.c:1085
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff8188a879)
Location: drivers/spi/spi.c:1105
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff8186d234)
Location: drivers/spi/spi.c:1117
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff818fd1b7)
Location: drivers/spi/spi.c:1181
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff81a4e846)
Location: drivers/spi/spi.c:1224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_transfer_wait(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer *xfer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1339
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81bd09f0-ffffffff81bd0b26: spi_transfer_wait (STB_LOCAL)
ffffffff8209cf54-ffffffff8209cf77: spi_transfer_wait.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff81c2d08c)
Location: drivers/spi/spi.c:1339
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_transfer_wait(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer *xfer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1409
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81cdaf80-ffffffff81cdb0d4: spi_transfer_wait (STB_LOCAL)
ffffffff821ff3bc-ffffffff821ff3d7: spi_transfer_wait.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c8d0c)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_transfer_wait(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer *xfer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf634)
Location: drivers/spi/spi.c:1058
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c0aaf634-c0aaf79c: spi_transfer_wait (STB_LOCAL)
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
In drivers/spi/spi.c (c000000000a8a7c0)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffe000618ec8)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff8177a0ad)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff81759e5d)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff817aa44d)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (ffffffff817c431f)
Location: drivers/spi/spi.c:1058
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>

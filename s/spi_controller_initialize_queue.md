# Function: <code>spi_controller_initialize_queue</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168cd9a)
Location: drivers/spi/spi.c:1497
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff816f6766)
Location: drivers/spi/spi.c:1501
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff81731c11)
Location: drivers/spi/spi.c:1499
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff81754601)
Location: drivers/spi/spi.c:1559
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff8178fc2b)
Location: drivers/spi/spi.c:1650
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817b3956)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff8187b014)
Location: drivers/spi/spi.c:1837
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_controller_initialize_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1879
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81886ad0-ffffffff81886bf8: spi_controller_initialize_queue (STB_LOCAL)
ffffffff81c18b90-ffffffff81c18bff: spi_controller_initialize_queue.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8186c654)
Location: drivers/spi/spi.c:1891
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
In drivers/spi/spi.c (ffffffff818fc4ea)
Location: drivers/spi/spi.c:1970
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
In drivers/spi/spi.c (ffffffff81a4db92)
Location: drivers/spi/spi.c:2014
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_controller_initialize_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2175
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81bd5780-ffffffff81bd5950: spi_controller_initialize_queue (STB_LOCAL)
ffffffff8209d168-ffffffff8209d17d: spi_controller_initialize_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spi_controller_initialize_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2182
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81c2c4b0-ffffffff81c2c67b: spi_controller_initialize_queue (STB_LOCAL)
ffffffff8211e03f-ffffffff8211e054: spi_controller_initialize_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_controller_initialize_queue(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2255
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81cdedd0-ffffffff81cdef9b: spi_controller_initialize_queue (STB_LOCAL)
ffffffff821ff5dd-ffffffff821ff5f2: spi_controller_initialize_queue.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c79dc)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (c0ab0ab8)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (c000000000a88498)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffe00061814a)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff81778436)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817581e6)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817a87d6)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817c2666)
Location: drivers/spi/spi.c:1652
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

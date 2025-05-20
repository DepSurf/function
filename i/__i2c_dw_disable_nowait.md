# Function: <code>__i2c_dw_disable_nowait</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da014)
Location: drivers/i2c/busses/i2c-designware-core.h:315
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db0be)
Location: drivers/i2c/busses/i2c-designware-core.h:315
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801224)
Location: drivers/i2c/busses/i2c-designware-core.h:305
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818026fc)
Location: drivers/i2c/busses/i2c-designware-core.h:305
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818425b8)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818435bd)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873f38)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874f3d)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819486a1)
Location: drivers/i2c/busses/i2c-designware-core.h:318
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949c84)
Location: drivers/i2c/busses/i2c-designware-core.h:318
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e4a1)
Location: drivers/i2c/busses/i2c-designware-core.h:318
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f954)
Location: drivers/i2c/busses/i2c-designware-core.h:318
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81932011)
Location: drivers/i2c/busses/i2c-designware-core.h:328
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819335ba)
Location: drivers/i2c/busses/i2c-designware-core.h:328
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5336)
Location: drivers/i2c/busses/i2c-designware-core.h:328
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d697d)
Location: drivers/i2c/busses/i2c-designware-core.h:328
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37d1d)
Location: drivers/i2c/busses/i2c-designware-core.h:340
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b394ec)
Location: drivers/i2c/busses/i2c-designware-core.h:340
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd2eb)
Location: drivers/i2c/busses/i2c-designware-core.h:339
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf247)
Location: drivers/i2c/busses/i2c-designware-core.h:339
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3504b)
Location: drivers/i2c/busses/i2c-designware-core.h:345
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37313)
Location: drivers/i2c/busses/i2c-designware-core.h:345
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb137)
Location: drivers/i2c/busses/i2c-designware-core.h:348
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded593)
Location: drivers/i2c/busses/i2c-designware-core.h:348
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8d54)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9d04)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b98350)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99340)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bc94)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d85c)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bdc18)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bee80)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818693e8)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a3ed)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883378)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8188437d)
Location: drivers/i2c/busses/i2c-designware-core.h:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
</ul>

## Differences

# Function: <code>create_syslog_header</code>

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
In drivers/base/core.c (ffffffff81547237)
Location: drivers/base/core.c:2106
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff81598eb7)
Location: drivers/base/core.c:2106
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff815c67f7)
Location: drivers/base/core.c:2697
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff815db5ab)
Location: drivers/base/core.c:2699
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff816425c7)
Location: drivers/base/core.c:2835
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff8167d8eb)
Location: drivers/base/core.c:2890
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff8169d2f7)
Location: drivers/base/core.c:2965
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff816d8a43)
Location: drivers/base/core.c:3219
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff816fcadc)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff817b6426)
Location: drivers/base/core.c:3839
Inline: True
Direct callers:
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff817b6426-ffffffff817b658c: create_syslog_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/base/core.c (ffff8000108e76c4)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (c09d5b48)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (c00000000097d920)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffe00057bd08)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff816c22cc)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff8169d57c)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff816f079c)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
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
In drivers/base/core.c (ffffffff8170afdc)
Location: drivers/base/core.c:3371
Inline: True
Inline callers:
  - drivers/base/core.c:dev_vprintk_emit
```
</details>
</li>
</ul>

## Differences

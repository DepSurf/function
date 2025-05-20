# Function: <code>scsi_io_completion_nz_result</code>

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
In drivers/scsi/scsi_lib.c (ffffffff817148d8)
Location: drivers/scsi/scsi_lib.c:842
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817501d6)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817743c6)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81836730)
Location: drivers/scsi/scsi_lib.c:819
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81836730-ffffffff818368a4: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81847200)
Location: drivers/scsi/scsi_lib.c:849
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81847200-ffffffff81847374: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff8182b4a6)
Location: drivers/scsi/scsi_lib.c:818
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5ac0)
Location: drivers/scsi/scsi_lib.c:818
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff818b5ac0-ffffffff818b5c52: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00fd0)
Location: drivers/scsi/scsi_lib.c:860
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81a00fd0-ffffffff81a01171: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81b81017)
Location: drivers/scsi/scsi_lib.c:866
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd2a90)
Location: drivers/scsi/scsi_lib.c:867
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81bd2a90-ffffffff81bd2c39: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27700)
Location: drivers/scsi/scsi_lib.c:866
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81c27700-ffffffff81c278a9: scsi_io_completion_nz_result.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffff800010978500)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (c0a4c2cc)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (c000000000a329e0)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffe0005dfefe)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81728ab6)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81701ee6)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81767886)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81782fc6)
Location: drivers/scsi/scsi_lib.c:835
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
</details>
</li>
</ul>

## Differences

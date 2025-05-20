# Function: <code>rdev_init_wb</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8186b296)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81861280-ffffffff818612cd: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8189d064)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81892eb0-ffffffff81892efd: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In drivers/md/md.c (ffff800010af1950)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (c0bd2e9c)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (c000000000bddf1c)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c000000000bd0300-c000000000bd0384: rdev_init_wb.part.0 (STB_LOCAL)
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
In drivers/md/md.c (ffffffe0006e56b6)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81842ee4)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81838d30-ffffffff81838d7d: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8180a544)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff818003a0-ffffffff818003ed: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81892514)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81888360-ffffffff818883ad: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff818ae0ef)
Location: drivers/md/md.c:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff818a5900-ffffffff818a594d: rdev_init_wb.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

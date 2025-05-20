# Function: <code>file_tty_write</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1098
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff817510b0-ffffffff81751165: file_tty_write.constprop.0 (STB_LOCAL)
ffffffff81c07372-ffffffff81c073a2: file_tty_write.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1114
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff817350c0-ffffffff81735175: file_tty_write.constprop.0 (STB_LOCAL)
ffffffff81bf8fdc-ffffffff81bf900c: file_tty_write.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1091
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff817b5ac0-ffffffff817b5b75: file_tty_write.constprop.0 (STB_LOCAL)
ffffffff81cf8779-ffffffff81cf87a9: file_tty_write.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1076
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff818f1c50-ffffffff818f1d0f: file_tty_write.constprop.0 (STB_LOCAL)
ffffffff81ec08ad-ffffffff81ec08db: file_tty_write.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4a1d0)
Location: drivers/tty/tty_io.c:1070
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81a4a1d0-ffffffff81a4a2d4: file_tty_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81a943f0)
Location: drivers/tty/tty_io.c:1079
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81a943f0-ffffffff81a944f7: file_tty_write.isra.0 (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81ae6fb0)
Location: drivers/tty/tty_io.c:1077
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81ae6fb0-ffffffff81ae70bc: file_tty_write.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

# Function: <code>nvm_remove_tgt</code>

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
In drivers/lightnvm/core.c (ffffffff815d9318)
Location: drivers/lightnvm/core.c:369
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff81640098)
Location: drivers/lightnvm/core.c:390
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff8167b67e)
Location: drivers/lightnvm/core.c:482
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff8169afde)
Location: drivers/lightnvm/core.c:487
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff816d38c7)
Location: drivers/lightnvm/core.c:479
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff816f77a7)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff817af3b0)
Location: drivers/lightnvm/core.c:480
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817af3b0-ffffffff817af4f6: nvm_remove_tgt.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817c3f30)
Location: drivers/lightnvm/core.c:476
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817c3f30-ffffffff817c4076: nvm_remove_tgt.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817a8091)
Location: drivers/lightnvm/core.c:476
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
</details>
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
In drivers/lightnvm/core.c (ffff8000108e1694)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (c09d02e0)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (c000000000975b20)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffe000576e24)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff816bcf97)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816eb467)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff81705ca7)
Location: drivers/lightnvm/core.c:481
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
</details>
</li>
</ul>

## Differences

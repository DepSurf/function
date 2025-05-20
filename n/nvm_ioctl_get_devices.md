# Function: <code>nvm_ioctl_get_devices</code>

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
In drivers/lightnvm/core.c (ffffffff81543f20)
Location: drivers/lightnvm/core.c:943
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff815953f2)
Location: drivers/lightnvm/core.c:950
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff815c2d52)
Location: drivers/lightnvm/core.c:908
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
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
In drivers/lightnvm/core.c (ffffffff815d9175)
Location: drivers/lightnvm/core.c:1204
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
In drivers/lightnvm/core.c (ffffffff8163fee3)
Location: drivers/lightnvm/core.c:1210
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
In drivers/lightnvm/core.c (ffffffff8167b730)
Location: drivers/lightnvm/core.c:1032
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
In drivers/lightnvm/core.c (ffffffff8169b090)
Location: drivers/lightnvm/core.c:1247
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
In drivers/lightnvm/core.c (ffffffff816d3960)
Location: drivers/lightnvm/core.c:1267
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
In drivers/lightnvm/core.c (ffffffff816f7850)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1295
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817ae5c0-ffffffff817ae73c: nvm_ioctl_get_devices.constprop.0 (STB_LOCAL)
ffffffff817b0625-ffffffff817b063c: nvm_ioctl_get_devices.constprop.0.cold (STB_LOCAL)
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
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1290
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817c3150-ffffffff817c32b4: nvm_ioctl_get_devices.constprop.0 (STB_LOCAL)
ffffffff81c0d8bc-ffffffff81c0d8f0: nvm_ioctl_get_devices.constprop.0.cold (STB_LOCAL)
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
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1292
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817a64f0-ffffffff817a6654: nvm_ioctl_get_devices.constprop.0 (STB_LOCAL)
ffffffff81bffc30-ffffffff81bffc64: nvm_ioctl_get_devices.constprop.0.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108e03e0)
Location: drivers/lightnvm/core.c:1296
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffff8000108e03e0-ffff8000108e0698: nvm_ioctl_get_devices.isra.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (c09d0430)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (c0000000009758cc)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (ffffffe000576ec2)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (ffffffff816bd040)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (ffffffff816eb510)
Location: drivers/lightnvm/core.c:1296
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
In drivers/lightnvm/core.c (ffffffff81705d50)
Location: drivers/lightnvm/core.c:1296
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
</details>
</li>
</ul>

## Differences

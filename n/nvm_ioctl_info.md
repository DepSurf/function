# Function: <code>nvm_ioctl_info</code>

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
In drivers/lightnvm/core.c (ffffffff81544139)
Location: drivers/lightnvm/core.c:902
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
In drivers/lightnvm/core.c (ffffffff81595561)
Location: drivers/lightnvm/core.c:909
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
In drivers/lightnvm/core.c (ffffffff815c2ec1)
Location: drivers/lightnvm/core.c:867
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
In drivers/lightnvm/core.c (ffffffff815d9397)
Location: drivers/lightnvm/core.c:1163
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
In drivers/lightnvm/core.c (ffffffff81640117)
Location: drivers/lightnvm/core.c:1169
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
In drivers/lightnvm/core.c (ffffffff8167b567)
Location: drivers/lightnvm/core.c:994
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
In drivers/lightnvm/core.c (ffffffff8169aec7)
Location: drivers/lightnvm/core.c:1209
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
In drivers/lightnvm/core.c (ffffffff816d37bf)
Location: drivers/lightnvm/core.c:1229
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
In drivers/lightnvm/core.c (ffffffff816f769f)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (ffffffff817ae470)
Location: drivers/lightnvm/core.c:1257
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817ae470-ffffffff817ae57e: nvm_ioctl_info.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817c3000)
Location: drivers/lightnvm/core.c:1252
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffffffff817c3000-ffffffff817c310e: nvm_ioctl_info.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817a7f8b)
Location: drivers/lightnvm/core.c:1254
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108e0168)
Location: drivers/lightnvm/core.c:1258
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
**Symbols:**

```
ffff8000108e0168-ffff8000108e03e0: nvm_ioctl_info.isra.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (c09d0198)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (c0000000009757a4)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (ffffffe000576d26)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (ffffffff816bce8f)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (ffffffff816eb35f)
Location: drivers/lightnvm/core.c:1258
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
In drivers/lightnvm/core.c (ffffffff81705b9f)
Location: drivers/lightnvm/core.c:1258
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
</details>
</li>
</ul>

## Differences

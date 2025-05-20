# Function: <code>ioctl_has_perm</code>

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
In security/selinux/hooks.c (ffffffff813470f9)
Location: security/selinux/hooks.c:3262
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8137c9a7)
Location: security/selinux/hooks.c:3345
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff81393457)
Location: security/selinux/hooks.c:3417
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff813a9bf1)
Location: security/selinux/hooks.c:3394
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff813cfe01)
Location: security/selinux/hooks.c:3409
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff81401da4)
Location: security/selinux/hooks.c:3575
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8141e024)
Location: security/selinux/hooks.c:3318
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8144b9f9)
Location: security/selinux/hooks.c:3506
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff81465679)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff814b7bb0)
Location: security/selinux/hooks.c:3557
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff814b7bb0-ffffffff814b7ca9: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff814d58c0)
Location: security/selinux/hooks.c:3577
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff814d58c0-ffffffff814d59b9: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff814dc7b9)
Location: security/selinux/hooks.c:3736
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff81535c69)
Location: security/selinux/hooks.c:3721
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff815cc000)
Location: security/selinux/hooks.c:3611
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff815cc000-ffffffff815cc147: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff816791f0)
Location: security/selinux/hooks.c:3629
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff816791f0-ffffffff81679337: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff816b13d0)
Location: security/selinux/hooks.c:3621
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff816b13d0-ffffffff816b150f: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff816ee3c0)
Location: security/selinux/hooks.c:3679
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff816ee3c0-ffffffff816ee4ff: ioctl_has_perm.constprop.0.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffff80001055382c)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (c0707038)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (c0000000006ad2ec)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffe0003ac38e)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8145dc59)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8144e689)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff81459cf9)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
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
In security/selinux/hooks.c (ffffffff8146fc59)
Location: security/selinux/hooks.c:3564
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
</details>
</li>
</ul>

## Differences

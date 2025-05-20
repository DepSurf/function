# Function: <code>seccomp_names_from_actions_logged</code>

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
In kernel/seccomp.c (ffffffff8114fc93)
Location: kernel/seccomp.c:1061
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_actions_logged_handler
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
In kernel/seccomp.c (ffffffff8115c244)
Location: kernel/seccomp.c:1089
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_actions_logged_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (ffffffff8116ae10)
Location: kernel/seccomp.c:1143
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff8116ae10-ffffffff8116aeb1: seccomp_names_from_actions_logged.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (ffffffff811783a0)
Location: kernel/seccomp.c:1590
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811783a0-ffffffff81178441: seccomp_names_from_actions_logged.constprop.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (ffffffff811852d0)
Location: kernel/seccomp.c:1605
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811852d0-ffffffff81185371: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811911f0)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811911f0-ffffffff81191291: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a5e30)
Location: kernel/seccomp.c:1649
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811a5e30-ffffffff811a5ed1: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a30a0)
Location: kernel/seccomp.c:2140
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811a30a0-ffffffff811a3141: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a3c80)
Location: kernel/seccomp.c:2188
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811a3c80-ffffffff811a3d21: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811cd360)
Location: kernel/seccomp.c:2170
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811cd360-ffffffff811cd401: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff812013b0)
Location: kernel/seccomp.c:2207
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff812013b0-ffffffff81201460: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81249130)
Location: kernel/seccomp.c:2207
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff81249130-ffffffff812491e0: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81260520)
Location: kernel/seccomp.c:2207
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff81260520-ffffffff812605d0: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff8127a6f0)
Location: kernel/seccomp.c:2271
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff8127a6f0-ffffffff8127a7a0: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
```
</details>
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
In kernel/seccomp.c (ffff8000102084e0)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffff8000102084e0-ffff8000102085b0: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (c04471a0)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
```
**Symbols:**

```
c04471a0-c0447250: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (c0000000002858f0)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
c0000000002858f0-c000000000285a38: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (ffffffe00016ad0c)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffe00016ad0c-ffffffe00016ada8: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81189810)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff81189810-ffffffff811898b1: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff8117c950)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff8117c950-ffffffff8117c9f1: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811875e0)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff811875e0-ffffffff81187681: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81194f30)
Location: kernel/seccomp.c:1628
Inline: True
Direct callers:
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:audit_actions_logged
  - kernel/seccomp.c:read_actions_logged
```
**Symbols:**

```
ffffffff81194f30-ffffffff81194fd1: seccomp_names_from_actions_logged.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

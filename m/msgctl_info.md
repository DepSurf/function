# Function: <code>msgctl_info</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (ffffffff813a9460)
Location: ipc/msg.c:440
Inline: True
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/msg.c:SYSC_msgctl
```
**Symbols:**

```
ffffffff813a9460-ffffffff813a9575: msgctl_info.isra.6 (STB_LOCAL)
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
In ipc/msg.c (ffffffff813d79a0)
Location: ipc/msg.c:454
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813d79a0-ffffffff813d7aac: msgctl_info.isra.9 (STB_LOCAL)
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
In ipc/msg.c (ffffffff813f1fb0)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813f1fb0-ffffffff813f20bc: msgctl_info.isra.9 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8141e2a0)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8141e2a0-ffffffff8141e3b3: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814380f0)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814380f0-ffffffff81438203: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81488050)
Location: ipc/msg.c:474
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81488050-ffffffff81488163: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814a5670)
Location: ipc/msg.c:474
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814a5670-ffffffff814a5783: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814ab630)
Location: ipc/msg.c:476
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814ab630-ffffffff814ab73a: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81503af0)
Location: ipc/msg.c:476
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81503af0-ffffffff81503bfa: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81595470)
Location: ipc/msg.c:476
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81595470-ffffffff81595584: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8163e3b0)
Location: ipc/msg.c:477
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8163e3b0-ffffffff8163e4e0: msgctl_info.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81676910)
Location: ipc/msg.c:477
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81676910-ffffffff81676a40: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff816b2cd0)
Location: ipc/msg.c:477
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff816b2cd0-ffffffff816b2e00: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffff80001051eb28)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffff80001051eb28-ffff80001051ec2c: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (c06dbf94)
Location: ipc/msg.c:455
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
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
In ipc/msg.c (c000000000668220)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
c000000000668220-c000000000668378: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffe000386780)
Location: ipc/msg.c:455
Inline: True
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
In ipc/msg.c (ffffffff814306d0)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814306d0-ffffffff814307e3: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81421150)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81421150-ffffffff81421263: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8142c870)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8142c870-ffffffff8142c983: msgctl_info.isra.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81443bc0)
Location: ipc/msg.c:455
Inline: True
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81443bc0-ffffffff81443cd3: msgctl_info.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

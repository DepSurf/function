# Function: <code>semctl_info</code>

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
In ipc/sem.c (ffffffff813ad2a8)
Location: ipc/sem.c:1228
Inline: True
Inline callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
```
**Symbols:**

```
ffffffff813aa550-ffffffff813aa667: semctl_info.isra.11.part.12 (STB_LOCAL)
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
In ipc/sem.c (ffffffff813dcdb9)
Location: ipc/sem.c:1286
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813d9400-ffffffff813d9516: semctl_info.isra.15.part.16 (STB_LOCAL)
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
In ipc/sem.c (ffffffff813f3ab0)
Location: ipc/sem.c:1293
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813f3ab0-ffffffff813f3bdd: semctl_info.isra.18 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8141ff00)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8141ff00-ffffffff8142002d: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81439d00)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81439d00-ffffffff81439e2d: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8148dd6a)
Location: ipc/sem.c:1305
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81489ea0-ffffffff81489fb6: semctl_info.part.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814ab4aa)
Location: ipc/sem.c:1304
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814a74c0-ffffffff814a75d4: semctl_info.part.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814b044a)
Location: ipc/sem.c:1306
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814ad400-ffffffff814ad514: semctl_info.part.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8150851a)
Location: ipc/sem.c:1309
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff815058c0-ffffffff815059d4: semctl_info.part.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff815973a0)
Location: ipc/sem.c:1308
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff815973a0-ffffffff815974fc: semctl_info.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81640480)
Location: ipc/sem.c:1308
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81640480-ffffffff816405dc: semctl_info.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff816789d0)
Location: ipc/sem.c:1308
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816789d0-ffffffff81678b2c: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff816b4dc0)
Location: ipc/sem.c:1308
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816b4dc0-ffffffff816b4f1c: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffff800010521fe0)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:__arm64_sys_semctl
```
**Symbols:**

```
ffff800010521fe0-ffff800010522170: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (c06dcf9c)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c06dcf9c-c06dd114: semctl_info.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (c00000000066acd0)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c00000000066acd0-c00000000066ae6c: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffe0003877ca)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
ffffffe0003877ca-ffffffe0003878c8: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814322e0)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814322e0-ffffffff8143240d: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81422d60)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81422d60-ffffffff81422e8d: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8142e480)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8142e480-ffffffff8142e5ad: semctl_info.isra.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814457e0)
Location: ipc/sem.c:1289
Inline: True
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814457e0-ffffffff8144590d: semctl_info.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

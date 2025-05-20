# Function: <code>ksys_semctl</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dcaf0)
Location: ipc/sem.c:1630
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff813dcaf0-ffffffff813dcc3f: ksys_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f7110)
Location: ipc/sem.c:1637
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff813f7110-ffffffff813f7281: ksys_semctl (STB_GLOBAL)
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
In ipc/sem.c (ffffffff81423680)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81423680-ffffffff81423811: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8143d3c0)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff8143d3c0-ffffffff8143d551: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8148df90)
Location: ipc/sem.c:1649
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff8148df90-ffffffff8148e136: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814ab6d0)
Location: ipc/sem.c:1648
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff814ab6d0-ffffffff814ab876: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff814b0670)
Location: ipc/sem.c:1650
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff814b0670-ffffffff814b0816: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81508740)
Location: ipc/sem.c:1653
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81508740-ffffffff815088e6: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8159a740)
Location: ipc/sem.c:1651
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff8159a740-ffffffff8159a8c4: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81643a20)
Location: ipc/sem.c:1651
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81643a20-ffffffff81643ba4: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8167bf70)
Location: ipc/sem.c:1651
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff8167bf70-ffffffff8167c0ea: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff816b8340)
Location: ipc/sem.c:1651
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff816b8340-ffffffff816b84ba: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffff800010525230)
Location: ipc/sem.c:1633
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_sys_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06de394)
Location: ipc/sem.c:1633
Inline: False
Direct callers:
  - ipc/sem.c:ksys_old_semctl
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
c06de394-c06dea48: ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066def0)
Location: ipc/sem.c:1633
Inline: False
Direct callers:
  - ipc/sem.c:ksys_old_semctl
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
c00000000066def0-c00000000066e148: ksys_semctl (STB_LOCAL)
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
In ipc/sem.c (ffffffe0003899fa)
Location: ipc/sem.c:1633
Inline: True
Inline callers:
  - ipc/sem.c:__se_sys_semctl
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
In ipc/sem.c (ffffffff814359a0)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff814359a0-ffffffff81435b31: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81426420)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81426420-ffffffff814265b1: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81431b40)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81431b40-ffffffff81431cd1: ksys_semctl.constprop.0 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81448c10)
Location: ipc/sem.c:1633
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semctl
  - ipc/sem.c:__x64_sys_semctl
```
**Symbols:**

```
ffffffff81448c10-ffffffff81448da1: ksys_semctl.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>

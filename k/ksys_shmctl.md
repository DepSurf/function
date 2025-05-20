# Function: <code>ksys_shmctl</code>

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
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813dedf0)
Location: ipc/shm.c:1111
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff813dedf0-ffffffff813def69: ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f94f0)
Location: ipc/shm.c:1140
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff813f94f0-ffffffff813f9697: ksys_shmctl (STB_GLOBAL)
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
In ipc/shm.c (ffffffff81425740)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff81425740-ffffffff814258f0: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8143f490)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff8143f490-ffffffff8143f640: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff814903e0)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff814903e0-ffffffff814905a4: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff814adb00)
Location: ipc/shm.c:1139
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff814adb00-ffffffff814adcc4: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff814b3950)
Location: ipc/shm.c:1139
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff814b3950-ffffffff814b3afc: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8150bfc0)
Location: ipc/shm.c:1235
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff8150bfc0-ffffffff8150c16c: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8159e0c0)
Location: ipc/shm.c:1229
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff8159e0c0-ffffffff8159e288: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff816476e0)
Location: ipc/shm.c:1245
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff816476e0-ffffffff816478ac: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8167fc10)
Location: ipc/shm.c:1245
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff8167fc10-ffffffff8167fdc2: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff816bc000)
Location: ipc/shm.c:1241
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff816bc000-ffffffff816bc1b2: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffff800010527ae8)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__arm64_sys_shmctl
```
**Symbols:**

```
ffff800010527ae8-ffff800010527d98: ksys_shmctl.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds *buf, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e0d58)
Location: ipc/shm.c:1140
Inline: False
Direct callers:
  - ipc/shm.c:ksys_old_shmctl
  - ipc/shm.c:__se_sys_shmctl
```
**Symbols:**

```
c06e0d58-c06e16bc: ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds *buf, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c0000000006722e0)
Location: ipc/shm.c:1140
Inline: False
Direct callers:
  - ipc/shm.c:ksys_old_shmctl
  - ipc/shm.c:__se_sys_shmctl
```
**Symbols:**

```
c0000000006722e0-c0000000006726b0: ksys_shmctl (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b28a)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__se_sys_shmctl
```
**Symbols:**

```
ffffffe00038b28a-ffffffe00038b918: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff81437a70)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff81437a70-ffffffff81437c20: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff814284e0)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff814284e0-ffffffff81428690: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff81433c10)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff81433c10-ffffffff81433dc0: ksys_shmctl.constprop.0 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8144a5d0)
Location: ipc/shm.c:1140
Inline: True
Direct callers:
  - ipc/shm.c:__ia32_sys_shmctl
  - ipc/shm.c:__x64_sys_shmctl
```
**Symbols:**

```
ffffffff8144a5d0-ffffffff8144a780: ksys_shmctl.constprop.0 (STB_LOCAL)
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

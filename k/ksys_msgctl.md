# Function: <code>ksys_msgctl</code>

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
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8db0)
Location: ipc/msg.c:560
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff813d8db0-ffffffff813d8eff: ksys_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f33d0)
Location: ipc/msg.c:570
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff813f33d0-ffffffff813f3537: ksys_msgctl (STB_GLOBAL)
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
In ipc/msg.c (ffffffff8141f2e0)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff8141f2e0-ffffffff8141f442: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81439100)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff81439100-ffffffff8143926e: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814891c0)
Location: ipc/msg.c:589
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff814891c0-ffffffff8148932e: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814a67e0)
Location: ipc/msg.c:589
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff814a67e0-ffffffff814a694e: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814ac750)
Location: ipc/msg.c:591
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff814ac750-ffffffff814ac8bf: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81504c30)
Location: ipc/msg.c:591
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff81504c30-ffffffff81504d9f: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81595db0)
Location: ipc/msg.c:591
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff81595db0-ffffffff81595f5c: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8163ec00)
Location: ipc/msg.c:597
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff8163ec00-ffffffff8163edac: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81677120)
Location: ipc/msg.c:597
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff81677120-ffffffff816772e0: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff816b34e0)
Location: ipc/msg.c:597
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff816b34e0-ffffffff816b36a0: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffff800010520c40)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__arm64_sys_msgctl
```
**Symbols:**

```
ffff800010520c40-ffff800010520de4: ksys_msgctl.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds *buf, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06dbd94)
Location: ipc/msg.c:570
Inline: False
Direct callers:
  - ipc/msg.c:ksys_old_msgctl
  - ipc/msg.c:__se_sys_msgctl
```
**Symbols:**

```
c06dbd94-c06dc17c: ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds *buf, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c0000000006695c0)
Location: ipc/msg.c:570
Inline: False
Direct callers:
  - ipc/msg.c:ksys_old_msgctl
  - ipc/msg.c:__se_sys_msgctl
```
**Symbols:**

```
c0000000006695c0-c0000000006697f0: ksys_msgctl (STB_LOCAL)
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
In ipc/msg.c (ffffffe0003865ce)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__se_sys_msgctl
```
**Symbols:**

```
ffffffe0003865ce-ffffffe000386900: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814316e0)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff814316e0-ffffffff8143184e: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81422160)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff81422160-ffffffff814222ce: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8142d880)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff8142d880-ffffffff8142d9ee: ksys_msgctl.constprop.0 (STB_LOCAL)
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
In ipc/msg.c (ffffffff814442b0)
Location: ipc/msg.c:570
Inline: True
Direct callers:
  - ipc/msg.c:__ia32_sys_msgctl
  - ipc/msg.c:__x64_sys_msgctl
```
**Symbols:**

```
ffffffff814442b0-ffffffff8144441e: ksys_msgctl.constprop.0 (STB_LOCAL)
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

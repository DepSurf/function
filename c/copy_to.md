# Function: <code>copy_to</code>

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
In fs/proc/vmcore.c (ffffffff812877ab)
Location: fs/proc/vmcore.c:170
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812b4960)
Location: fs/proc/vmcore.c:170
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812b4960-ffffffff812b49a7: copy_to.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812ca1f0)
Location: fs/proc/vmcore.c:170
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812ca1f0-ffffffff812ca237: copy_to.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812d7832)
Location: fs/proc/vmcore.c:170
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812d7580-ffffffff812d75c7: copy_to.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812fbf12)
Location: fs/proc/vmcore.c:170
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812fbc60-ffffffff812fbca7: copy_to.part.3 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813298d4)
Location: fs/proc/vmcore.c:182
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81329590-ffffffff813295d7: copy_to.part.4 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff81341051)
Location: fs/proc/vmcore.c:203
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81340840-ffffffff81340887: copy_to.part.4 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff81369449)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81368ba0-ffffffff81368be9: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff81381699)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81380df0-ffffffff81380e4a: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813cb3a0)
Location: fs/proc/vmcore.c:207
Inline: True
```
**Symbols:**

```
ffffffff813cb3a0-ffffffff813cb3fa: copy_to.constprop.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813dd050)
Location: fs/proc/vmcore.c:207
Inline: True
```
**Symbols:**

```
ffffffff813dd050-ffffffff813dd0aa: copy_to.constprop.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813e3f40)
Location: fs/proc/vmcore.c:207
Inline: True
```
**Symbols:**

```
ffffffff813e3f40-ffffffff813e3f97: copy_to.constprop.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff81435af0)
Location: fs/proc/vmcore.c:211
Inline: True
```
**Symbols:**

```
ffffffff81435af0-ffffffff81435b47: copy_to.constprop.0 (STB_LOCAL)
```
</details>
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
In fs/proc/vmcore.c (ffff80001044f578)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffff80001044eac0-ffff80001044ec70: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (c0612acc)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
c0611e8c-c0611f68: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (c000000000567460)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
c000000000566790-c00000000056683c: copy_to.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/proc/vmcore.c (ffffffff81379c79)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff813793d0-ffffffff8137942a: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff8136a749)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81369ea0-ffffffff81369efa: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff81377749)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81376ea0-ffffffff81376efa: copy_to.part.0 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff8138b1f9)
Location: fs/proc/vmcore.c:208
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff8138a950-ffffffff8138a9aa: copy_to.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

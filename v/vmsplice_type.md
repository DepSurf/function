# Function: <code>vmsplice_type</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff812d13c0)
Location: fs/splice.c:1300
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff812d13c0-ffffffff812d140d: vmsplice_type.isra.17 (STB_LOCAL)
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
In fs/splice.c (ffffffff812e64d0)
Location: fs/splice.c:1304
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff812e64d0-ffffffff812e651d: vmsplice_type.isra.18 (STB_LOCAL)
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
In fs/splice.c (ffffffff81305130)
Location: fs/splice.c:1310
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81305130-ffffffff8130517d: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff813181c0)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813181c0-ffffffff8131820d: vmsplice_type.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135163f)
Location: fs/splice.c:1306
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135dddb)
Location: fs/splice.c:1260
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81364c4f)
Location: fs/splice.c:1265
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff813b311f)
Location: fs/splice.c:1267
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81438232)
Location: fs/splice.c:1263
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c66d2)
Location: fs/splice.c:1263
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fc0f7)
Location: fs/splice.c:1504
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81530ed7)
Location: fs/splice.c:1567
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffff8000103ce1a8)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffff8000103ce1a8-ffff8000103ce234: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (c05a9cac)
Location: fs/splice.c:1318
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (c0000000004d1410)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
c0000000004d1410-c0000000004d14ac: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (ffffffe00028b566)
Location: fs/splice.c:1318
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff813107a0)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813107a0-ffffffff813107ed: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff813013b0)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813013b0-ffffffff813013fd: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff8130e590)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff8130e590-ffffffff8130e5dd: vmsplice_type.isra.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff8131fd90)
Location: fs/splice.c:1318
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff8131fd90-ffffffff8131fddd: vmsplice_type.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences

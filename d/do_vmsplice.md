# Function: <code>do_vmsplice</code>

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
In fs/splice.c (ffffffff812d1611)
Location: fs/splice.c:1331
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff812d1290-ffffffff812d13b5: do_vmsplice.part.15 (STB_LOCAL)
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
In fs/splice.c (ffffffff812e6a71)
Location: fs/splice.c:1335
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff812e6740-ffffffff812e6865: do_vmsplice.part.16 (STB_LOCAL)
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
In fs/splice.c (ffffffff813056f4)
Location: fs/splice.c:1341
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813053c0-ffffffff813054e6: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff81318784)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81318450-ffffffff81318576: do_vmsplice.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int do_vmsplice(struct file *f, struct iov_iter *iter, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81351300)
Location: fs/splice.c:1337
Inline: True
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81351300-ffffffff8135149d: do_vmsplice (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In fs/splice.c (ffff8000103ce868)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffff8000103ce520-ffff8000103ce674: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (c05a9d24)
Location: fs/splice.c:1349
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
In fs/splice.c (c0000000004d1d28)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
c0000000004d1900-c0000000004d1ac0: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (ffffffe00028b5bc)
Location: fs/splice.c:1349
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
In fs/splice.c (ffffffff81310d64)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81310a30-ffffffff81310b56: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff81301974)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81301640-ffffffff81301766: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff8130eb54)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff8130e820-ffffffff8130e946: do_vmsplice.part.0 (STB_LOCAL)
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
In fs/splice.c (ffffffff81320354)
Location: fs/splice.c:1349
Inline: True
Inline callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
Direct callers:
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81320020-ffffffff81320146: do_vmsplice.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

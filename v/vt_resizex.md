# Function: <code>vt_resizex</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (0)
Location: drivers/tty/vt/vt_ioctl.c:766
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81760100-ffffffff817601bc: vt_resizex.constprop.0 (STB_LOCAL)
ffffffff81c078b0-ffffffff81c078e0: vt_resizex.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81743b90)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81743b90-ffffffff81743d20: vt_resizex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c48b0)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff817c48b0-ffffffff817c4a87: vt_resizex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81901640)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81901640-ffffffff81901855: vt_resizex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5b580)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81a5b580-ffffffff81a5b795: vt_resizex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa5bb0)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81aa5bb0-ffffffff81aa5dc5: vt_resizex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vt_resizex(struct vc_data *vc, struct vt_consize *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af8640)
Location: drivers/tty/vt/vt_ioctl.c:668
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81af8640-ffffffff81af8855: vt_resizex (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

# Function: <code>loop_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156dc50)
Location: drivers/block/loop.c:1868
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff8156dc50-ffffffff8156dc98: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c3540)
Location: drivers/block/loop.c:1868
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff815c3540-ffffffff815c3588: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f1c60)
Location: drivers/block/loop.c:1838
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff815f1c60-ffffffff815f1ca8: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81605e60)
Location: drivers/block/loop.c:1886
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff81605e60-ffffffff81605ea8: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166e260)
Location: drivers/block/loop.c:1918
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff8166e260-ffffffff8166e2a8: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816a9d40)
Location: drivers/block/loop.c:1979
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff816a9d40-ffffffff816a9d88: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ca930)
Location: drivers/block/loop.c:2068
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff816ca930-ffffffff816ca978: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81705ef0)
Location: drivers/block/loop.c:2119
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff81705ef0-ffffffff81705f3d: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172a140)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff8172a140-ffffffff8172a18d: loop_remove (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817e83c5)
Location: drivers/block/loop.c:2240
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit_cb
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
In drivers/block/loop.c (ffffffff817fd2f5)
Location: drivers/block/loop.c:2232
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit_cb
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
In drivers/block/loop.c (ffffffff817e1e45)
Location: drivers/block/loop.c:2245
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186cb70)
Location: drivers/block/loop.c:2465
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff8186cb70-ffffffff8186cbda: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b5690)
Location: drivers/block/loop.c:2061
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
```
**Symbols:**

```
ffffffff819b5690-ffffffff819b5708: loop_remove (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff842b1410)
Location: drivers/block/loop.c:2070
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
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
In drivers/block/loop.c (ffffffff83af4000)
Location: drivers/block/loop.c:2112
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
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
In drivers/block/loop.c (ffffffff83d4fd30)
Location: drivers/block/loop.c:2107
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010920e30)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffff800010920e30-ffff800010920e7c: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a05b74)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
c0a05b74-c0a05bb8: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c4de0)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
c0000000009c4de0-c0000000009c4e54: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059f6ea)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffe00059f6ea-ffffffe00059f744: loop_remove (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816eff20)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff816eff20-ffffffff816eff6d: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ca030)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff816ca030-ffffffff816ca07d: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171d600)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff8171d600-ffffffff8171d64d: loop_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void loop_remove(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81738990)
Location: drivers/block/loop.c:2140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit_cb
```
**Symbols:**

```
ffffffff81738990-ffffffff817389dd: loop_remove (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

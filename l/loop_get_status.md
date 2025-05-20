# Function: <code>loop_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156e850)
Location: drivers/block/loop.c:1223
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_get_status64
```
**Symbols:**

```
ffffffff8156e850-ffffffff8156ea5a: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c4140)
Location: drivers/block/loop.c:1218
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff815c4140-ffffffff815c4357: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f2890)
Location: drivers/block/loop.c:1189
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff815f2890-ffffffff815f2aa7: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81606ac0)
Location: drivers/block/loop.c:1233
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff81606ac0-ffffffff81606cdb: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166eee0)
Location: drivers/block/loop.c:1221
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff8166eee0-ffffffff8166f0fb: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816aa9d0)
Location: drivers/block/loop.c:1261
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff816aa9d0-ffffffff816aabf4: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff816cc070)
Location: drivers/block/loop.c:1341
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff816cc070-ffffffff816cc29a: loop_get_status.part.27 (STB_LOCAL)
ffffffff816cc2a0-ffffffff816cc2ee: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81707670)
Location: drivers/block/loop.c:1392
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff81707670-ffffffff817078be: loop_get_status.part.0 (STB_LOCAL)
ffffffff817078c0-ffffffff81707912: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff8172b8c0)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff8172b8c0-ffffffff8172bb0e: loop_get_status.part.0 (STB_LOCAL)
ffffffff8172bb10-ffffffff8172bb62: loop_get_status (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817e8515)
Location: drivers/block/loop.c:1484
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff817e7640-ffffffff817e786d: loop_get_status.part.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817fd945)
Location: drivers/block/loop.c:1475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff817fc270-ffffffff817fc49d: loop_get_status.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e05e0)
Location: drivers/block/loop.c:1492
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff817e05e0-ffffffff817e0846: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186c400)
Location: drivers/block/loop.c:1629
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff8186c400-ffffffff8186c666: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b5000)
Location: drivers/block/loop.c:1328
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff819b5000-ffffffff819b51da: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2a400)
Location: drivers/block/loop.c:1328
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff81b2a400-ffffffff81b2a5da: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7a7e0)
Location: drivers/block/loop.c:1328
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff81b7a7e0-ffffffff81b7a9c0: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bce5b0)
Location: drivers/block/loop.c:1322
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff81bce5b0-ffffffff81bce790: loop_get_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffff800010921db0)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffff800010921db0-ffff800010921f54: loop_get_status.part.0 (STB_LOCAL)
ffff800010921f58-ffff800010921fc8: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (c0a07600)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
c0a07600-c0a077d0: loop_get_status.part.0 (STB_LOCAL)
c0a077d0-c0a0782c: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (c0000000009c6b80)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
c0000000009c6b80-c0000000009c6da8: loop_get_status.part.0 (STB_LOCAL)
c0000000009c6db0-c0000000009c6e58: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a086e)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffe0005a086e-ffffffe0005a09c0: loop_get_status.part.0 (STB_LOCAL)
ffffffe0005a09c0-ffffffe0005a0a22: loop_get_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff816f16a0)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff816f16a0-ffffffff816f18ee: loop_get_status.part.0 (STB_LOCAL)
ffffffff816f18f0-ffffffff816f1942: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff816cb7a0)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff816cb7a0-ffffffff816cb9ee: loop_get_status.part.0 (STB_LOCAL)
ffffffff816cb9f0-ffffffff816cba42: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff8171ed80)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff8171ed80-ffffffff8171efce: loop_get_status.part.0 (STB_LOCAL)
ffffffff8171efd0-ffffffff8171f022: loop_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int loop_get_status(struct loop_device *lo, struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff8173a1b0)
Location: drivers/block/loop.c:1412
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
**Symbols:**

```
ffffffff8173a1b0-ffffffff8173a3fe: loop_get_status.part.0 (STB_LOCAL)
ffffffff8173a400-ffffffff8173a452: loop_get_status (STB_LOCAL)
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

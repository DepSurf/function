# Function: <code>__do_SAK</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e3630)
Location: drivers/tty/tty_io.c:3043
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff814e3630-ffffffff814e37bd: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534920)
Location: drivers/tty/tty_io.c:3056
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81534920-ffffffff81534b1d: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81561050)
Location: drivers/tty/tty_io.c:3056
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81561050-ffffffff8156124d: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81574555)
Location: drivers/tty/tty_io.c:2603
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81574360-ffffffff8157454e: __do_SAK.part.25 (STB_LOCAL)
ffffffff81574e40-ffffffff81574e57: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d76d5)
Location: drivers/tty/tty_io.c:2710
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff815d74e0-ffffffff815d76ce: __do_SAK.part.27 (STB_LOCAL)
ffffffff815d9630-ffffffff815d9647: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610a75)
Location: drivers/tty/tty_io.c:2728
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81610970-ffffffff81610a65: __do_SAK.part.29 (STB_LOCAL)
ffffffff8161310c-ffffffff8161321a: __do_SAK.part.29.cold.37 (STB_LOCAL)
ffffffff816125c0-ffffffff816125d6: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d7b5)
Location: drivers/tty/tty_io.c:2883
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff8162d6b0-ffffffff8162d7a5: __do_SAK.part.28 (STB_LOCAL)
ffffffff816301ac-ffffffff816302ce: __do_SAK.part.28.cold.36 (STB_LOCAL)
ffffffff8162f660-ffffffff8162f676: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816613e5)
Location: drivers/tty/tty_io.c:2887
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff816612d0-ffffffff816613d4: __do_SAK.part.0 (STB_LOCAL)
ffffffff816640b1-ffffffff816641d0: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff81663520-ffffffff81663536: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683a35)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81683920-ffffffff81683a24: __do_SAK.part.0 (STB_LOCAL)
ffffffff81686721-ffffffff8168683d: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff81685b90-ffffffff81685ba6: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735265)
Location: drivers/tty/tty_io.c:2892
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81735150-ffffffff81735255: __do_SAK.part.0 (STB_LOCAL)
ffffffff817384df-ffffffff817385ff: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff817375f0-ffffffff81737606: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81751d85)
Location: drivers/tty/tty_io.c:2980
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81751bd0-ffffffff81751d7b: __do_SAK.part.0 (STB_LOCAL)
ffffffff81c0743a-ffffffff81c0755f: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff817539b0-ffffffff817539c6: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817359d5)
Location: drivers/tty/tty_io.c:3029
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81735820-ffffffff817359c7: __do_SAK.part.0 (STB_LOCAL)
ffffffff81bf9060-ffffffff81bf9185: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff81737850-ffffffff81737866: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b6395)
Location: drivers/tty/tty_io.c:3029
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff817b61e0-ffffffff817b6387: __do_SAK.part.0 (STB_LOCAL)
ffffffff81cf87fd-ffffffff81cf8922: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff817b82e0-ffffffff817b82f6: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3002
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81ec0ab5-ffffffff81ec0c1f: __do_SAK.cold (STB_LOCAL)
ffffffff818f40c0-ffffffff818f4264: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4c790)
Location: drivers/tty/tty_io.c:3001
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81a4c790-ffffffff81a4cab2: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96a80)
Location: drivers/tty/tty_io.c:3010
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81a96a80-ffffffff81a96da2: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae9470)
Location: drivers/tty/tty_io.c:3027
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81ae9470-ffffffff81ae97c7: __do_SAK (STB_GLOBAL)
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
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010850350)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffff800010850088-ffff800010850338: __do_SAK.part.0 (STB_LOCAL)
ffff8000108535f8-ffff800010853628: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (c095cb04)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
c095c8a8-c095caf0: __do_SAK.part.0 (STB_LOCAL)
c095df6c-c095df90: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f0890)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
c0000000008f0580-c0000000008f0880: __do_SAK.part.0 (STB_LOCAL)
c0000000008f2980-c0000000008f299c: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052e710)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffe00052e4ee-ffffffe00052e6f6: __do_SAK.part.0 (STB_LOCAL)
ffffffe00052feb8-ffffffe00052fee4: __do_SAK (STB_GLOBAL)
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
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816494b5)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff816493a0-ffffffff816494a4: __do_SAK.part.0 (STB_LOCAL)
ffffffff8164c1a1-ffffffff8164c2bd: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff8164b610-ffffffff8164b626: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629915)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81629800-ffffffff81629904: __do_SAK.part.0 (STB_LOCAL)
ffffffff8162c5f1-ffffffff8162c70d: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff8162ba60-ffffffff8162ba76: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677875)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81677760-ffffffff81677864: __do_SAK.part.0 (STB_LOCAL)
ffffffff8167a561-ffffffff8167a67d: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff816799d0-ffffffff816799e6: __do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691b95)
Location: drivers/tty/tty_io.c:2889
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK_work
Direct callers:
  - drivers/tty/tty_io.c:do_SAK_work
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
```
**Symbols:**

```
ffffffff81691a90-ffffffff81691b8e: __do_SAK.part.0 (STB_LOCAL)
ffffffff81694bea-ffffffff81694d0a: __do_SAK.part.0.cold (STB_LOCAL)
ffffffff81694030-ffffffff81694046: __do_SAK (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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

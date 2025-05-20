# Function: <code>backlight_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff8146b2a0)
Location: drivers/video/backlight/backlight.c:407
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff8146b2a0-ffffffff8146b352: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff814b95f0)
Location: drivers/video/backlight/backlight.c:416
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff814b95f0-ffffffff814b96a2: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff814db600)
Location: drivers/video/backlight/backlight.c:416
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff814db600-ffffffff814db6ac: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff814e7458)
Location: drivers/video/backlight/backlight.c:421
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff814e7390-ffffffff814e742e: backlight_device_unregister.part.3 (STB_LOCAL)
ffffffff814e7430-ffffffff814e7447: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff8151bf58)
Location: drivers/video/backlight/backlight.c:421
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff8151be90-ffffffff8151bf2e: backlight_device_unregister.part.3 (STB_LOCAL)
ffffffff8151bf30-ffffffff8151bf47: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81551c08)
Location: drivers/video/backlight/backlight.c:421
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81551b40-ffffffff81551bde: backlight_device_unregister.part.4 (STB_LOCAL)
ffffffff81551be0-ffffffff81551bf6: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81569498)
Location: drivers/video/backlight/backlight.c:421
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff815693d0-ffffffff8156946e: backlight_device_unregister.part.4 (STB_LOCAL)
ffffffff81569470-ffffffff81569486: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81599d28)
Location: drivers/video/backlight/backlight.c:422
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81599c60-ffffffff81599cfc: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81599d00-ffffffff81599d16: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815bb0d8)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff815bb000-ffffffff815bb0a2: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff815bb0b0-ffffffff815bb0c6: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81664f98)
Location: drivers/video/backlight/backlight.c:462
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81664ec0-ffffffff81664f62: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81664f70-ffffffff81664f86: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81685c28)
Location: drivers/video/backlight/backlight.c:508
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81685b50-ffffffff81685bf2: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81685c00-ffffffff81685c16: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81668a28)
Location: drivers/video/backlight/backlight.c:508
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81668950-ffffffff816689f2: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81668a00-ffffffff81668a16: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff816dbd58)
Location: drivers/video/backlight/backlight.c:508
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff816dbc80-ffffffff816dbd22: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff816dbd30-ffffffff816dbd46: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81805a68)
Location: drivers/video/backlight/backlight.c:520
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81805980-ffffffff81805a2e: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81805a30-ffffffff81805a52: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81934448)
Location: drivers/video/backlight/backlight.c:520
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81934340-ffffffff819343ee: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff81934400-ffffffff81934422: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81978908)
Location: drivers/video/backlight/backlight.c:520
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff81978800-ffffffff819788ae: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff819788c0-ffffffff819788e2: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff819c29f8)
Location: drivers/video/backlight/backlight.c:520
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff819c28f0-ffffffff819c299e: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff819c29b0-ffffffff819c29d2: backlight_device_unregister (STB_GLOBAL)
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
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffff800010741fc4)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
```
**Symbols:**

```
ffff800010741ed8-ffff800010741f74: backlight_device_unregister.part.0 (STB_LOCAL)
ffff800010741f78-ffff800010741fa8: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (c08c6968)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
```
**Symbols:**

```
c08c68a0-c08c692c: backlight_device_unregister.part.0 (STB_LOCAL)
c08c692c-c08c6950: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (c0000000008a2334)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
c0000000008a2200-c0000000008a22f8: backlight_device_unregister.part.0 (STB_LOCAL)
c0000000008a2300-c0000000008a231c: backlight_device_unregister (STB_GLOBAL)
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

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815af228)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff815af150-ffffffff815af1f2: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff815af200-ffffffff815af216: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff8159e3b8)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff8159e2e0-ffffffff8159e382: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff8159e390-ffffffff8159e3a6: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815af7b8)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff815af6e0-ffffffff815af782: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff815af790-ffffffff815af7a6: backlight_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void backlight_device_unregister(struct backlight_device *bd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815c9228)
Location: drivers/video/backlight/backlight.c:441
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
Direct callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_release
```
**Symbols:**

```
ffffffff815c9150-ffffffff815c91f2: backlight_device_unregister.part.0 (STB_LOCAL)
ffffffff815c9200-ffffffff815c9216: backlight_device_unregister (STB_GLOBAL)
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

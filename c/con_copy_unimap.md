# Function: <code>con_copy_unimap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff814f60d0)
Location: drivers/tty/vt/consolemap.c:714
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff814f60d0-ffffffff814f6136: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81546c10)
Location: drivers/tty/vt/consolemap.c:713
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81546c10-ffffffff81546c76: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff815732b0)
Location: drivers/tty/vt/consolemap.c:735
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff815732b0-ffffffff81573316: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81587350)
Location: drivers/tty/vt/consolemap.c:713
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81587350-ffffffff815873b6: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff815ebe50)
Location: drivers/tty/vt/consolemap.c:714
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff815ebe50-ffffffff815ebeb6: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff816250a0)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff816250a0-ffffffff81625106: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81642590)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81642590-ffffffff816425f6: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81676b30)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81676b30-ffffffff81676b96: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff816992d0)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff816992d0-ffffffff81699336: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff8174b560)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff8174b560-ffffffff8174b5f1: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81766c70)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81766c70-ffffffff81766d01: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff8174a8c0)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff8174a8c0-ffffffff8174a94d: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff817cc140)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff817cc140-ffffffff817cc1cd: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81909a80)
Location: drivers/tty/vt/consolemap.c:715
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81909a80-ffffffff81909b1a: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81a64100)
Location: drivers/tty/vt/consolemap.c:763
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81a64100-ffffffff81a6419a: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81aae7b0)
Location: drivers/tty/vt/consolemap.c:763
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81aae7b0-ffffffff81aae84a: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff81b014a0)
Location: drivers/tty/vt/consolemap.c:763
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff81b014a0-ffffffff81b0153a: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffff80001086fef8)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffff80001086fef8-ffff80001086ff78: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (c097329c)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
c097329c-c0973310: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (c00000000090fe70)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
c00000000090fe70-c00000000090ff2c: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffe00054248c)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffe00054248c-ffffffe0005424f0: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff8165ed30)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff8165ed30-ffffffff8165ed96: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff8163f0b0)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff8163f0b0-ffffffff8163f116: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff8168d110)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff8168d110-ffffffff8168d176: con_copy_unimap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int con_copy_unimap(struct vc_data *dst_vc, struct vc_data *src_vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/consolemap.c (ffffffff816a7710)
Location: drivers/tty/vt/consolemap.c:715
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
**Symbols:**

```
ffffffff816a7710-ffffffff816a7776: con_copy_unimap (STB_GLOBAL)
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

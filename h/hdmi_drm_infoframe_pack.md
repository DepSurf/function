# Function: <code>hdmi_drm_infoframe_pack</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81595ff0)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff81595ff0-ffffffff8159601c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b7270)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815b7270-ffffffff815b729c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8166173e)
Location: drivers/video/hdmi.c:780
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff81660ec0-ffffffff81660eec: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81682b3e)
Location: drivers/video/hdmi.c:784
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff81682180-ffffffff816821ac: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8166595d)
Location: drivers/video/hdmi.c:784
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff81664fa0-ffffffff81664fcc: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816d895d)
Location: drivers/video/hdmi.c:784
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff816d7c00-ffffffff816d7c2c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff818028aa)
Location: drivers/video/hdmi.c:784
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff818017f0-ffffffff81801830: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8193063a)
Location: drivers/video/hdmi.c:828
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff8192f640-ffffffff8192f680: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81974a8a)
Location: drivers/video/hdmi.c:828
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff81973ab0-ffffffff81973af0: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819beafa)
Location: drivers/video/hdmi.c:828
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff819bdb20-ffffffff819bdb60: hdmi_drm_infoframe_pack (STB_GLOBAL)
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
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073fc88)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffff80001073fc88-ffff80001073fcf8: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c49cc)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
c08c49cc-c08c4a14: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c000000000899860)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
c000000000899860-c0000000008998a8: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004ef0b6)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffe0004ef0b6-ffffffe0004ef112: hdmi_drm_infoframe_pack (STB_GLOBAL)
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
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab4e0)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815ab4e0-ffffffff815ab50c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159a680)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff8159a680-ffffffff8159a6ac: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815aba70)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815aba70-ffffffff815aba9c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t hdmi_drm_infoframe_pack(struct hdmi_drm_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c5400)
Location: drivers/video/hdmi.c:784
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815c5400-ffffffff815c542c: hdmi_drm_infoframe_pack (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

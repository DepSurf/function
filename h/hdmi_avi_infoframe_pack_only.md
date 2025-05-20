# Function: <code>hdmi_avi_infoframe_pack_only</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815656e0)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff815656e0-ffffffff8156589d: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81595ac0)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff81595ac0-ffffffff81595c89: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b6d40)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff815b6d40-ffffffff815b6f09: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81660990)
Location: drivers/video/hdmi.c:109
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81660990-ffffffff81660b59: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81681c50)
Location: drivers/video/hdmi.c:109
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81681c50-ffffffff81681e19: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81664a70)
Location: drivers/video/hdmi.c:109
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81664a70-ffffffff81664c39: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:109
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81ceb754-ffffffff81ceb76e: hdmi_avi_infoframe_pack_only.cold (STB_LOCAL)
ffffffff816d7ed0-ffffffff816d80d8: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:109
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81eb2b75-ffffffff81eb2b8a: hdmi_avi_infoframe_pack_only.cold (STB_LOCAL)
ffffffff81801b00-ffffffff81801d17: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:110
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff820902ff-ffffffff82090314: hdmi_avi_infoframe_pack_only.cold (STB_LOCAL)
ffffffff8192f920-ffffffff8192fb37: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:110
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff8211065f-ffffffff82110674: hdmi_avi_infoframe_pack_only.cold (STB_LOCAL)
ffffffff81973d90-ffffffff81973f88: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:110
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff821ee45c-ffffffff821ee471: hdmi_avi_infoframe_pack_only.cold (STB_LOCAL)
ffffffff819bde00-ffffffff819bdff8: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073f650)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffff80001073f650-ffff80001073f844: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c43b4)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
c08c43b4-c08c45d8: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c0000000008991b0)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
c0000000008991b0-c00000000089940c: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004eeafe)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffe0004eeafe-ffffffe0004eecda: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815aafb0)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff815aafb0-ffffffff815ab179: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159a150)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff8159a150-ffffffff8159a319: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab540)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff815ab540-ffffffff815ab709: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t hdmi_avi_infoframe_pack_only(const struct hdmi_avi_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c4ed0)
Location: drivers/video/hdmi.c:113
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_avi_infoframe_pack
```
**Symbols:**

```
ffffffff815c4ed0-ffffffff815c5099: hdmi_avi_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

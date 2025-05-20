# Function: <code>hdmi_audio_infoframe_pack_only</code>

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
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81565910)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81565910-ffffffff81565a17: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81595d00)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81595d00-ffffffff81595e04: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b6f80)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff815b6f80-ffffffff815b7084: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81660bd0)
Location: drivers/video/hdmi.c:400
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81660bd0-ffffffff81660cd4: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81681e90)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81681e90-ffffffff81681f94: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81664cb0)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81664cb0-ffffffff81664db3: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81ceb76e-ffffffff81ceb787: hdmi_audio_infoframe_pack_only.cold (STB_LOCAL)
ffffffff816d8110-ffffffff816d8235: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81eb2b8a-ffffffff81eb2b9e: hdmi_audio_infoframe_pack_only.cold (STB_LOCAL)
ffffffff81801d70-ffffffff81801ea4: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8192f740)
Location: drivers/video/hdmi.c:427
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff8192f740-ffffffff8192f804: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81973bb0)
Location: drivers/video/hdmi.c:427
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff81973bb0-ffffffff81973c74: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819bdc20)
Location: drivers/video/hdmi.c:427
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff819bdc20-ffffffff819bdce4: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073f900)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffff80001073f900-ffff80001073fa2c: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c4670)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
c08c4670-c08c479c: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c0000000008994a0)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
c0000000008994a0-c00000000089961c: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004eed78)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffe0004eed78-ffffffe0004eee86: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab1f0)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff815ab1f0-ffffffff815ab2f4: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159a390)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff8159a390-ffffffff8159a494: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab780)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff815ab780-ffffffff815ab884: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t hdmi_audio_infoframe_pack_only(const struct hdmi_audio_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c5110)
Location: drivers/video/hdmi.c:404
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
```
**Symbols:**

```
ffffffff815c5110-ffffffff815c5214: hdmi_audio_infoframe_pack_only (STB_GLOBAL)
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

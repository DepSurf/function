# Function: <code>hdmi_vendor_infoframe_pack_only</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815666d0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815666d0-ffffffff815667b4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815967c0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815967c0-ffffffff815968a4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b79b0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815b79b0-ffffffff815b7a94: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661518)
Location: drivers/video/hdmi.c:563
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81661050-ffffffff81661105: hdmi_vendor_infoframe_pack_only.part.0 (STB_LOCAL)
ffffffff81661240-ffffffff816612a8: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81682918)
Location: drivers/video/hdmi.c:567
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81682450-ffffffff81682505: hdmi_vendor_infoframe_pack_only.part.0 (STB_LOCAL)
ffffffff81682640-ffffffff816826a8: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8166574e)
Location: drivers/video/hdmi.c:567
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81665270-ffffffff81665325: hdmi_vendor_infoframe_pack_only.part.0 (STB_LOCAL)
ffffffff816653d0-ffffffff81665438: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816d874e)
Location: drivers/video/hdmi.c:567
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff816d8270-ffffffff816d8325: hdmi_vendor_infoframe_pack_only.part.0 (STB_LOCAL)
ffffffff816d83d0-ffffffff816d8438: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff818014d0)
Location: drivers/video/hdmi.c:567
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff818014d0-ffffffff818015c4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8192f2f0)
Location: drivers/video/hdmi.c:611
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff8192f2f0-ffffffff8192f3e4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81973760)
Location: drivers/video/hdmi.c:611
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81973760-ffffffff81973855: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819bd7d0)
Location: drivers/video/hdmi.c:611
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff819bd7d0-ffffffff819bd8c5: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff800010740d48)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffff800010740d48-ffff800010740e74: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c58b0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
c08c58b0-c08c59c4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c00000000089abf0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
c00000000089abf0-c00000000089ad70: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004f0026)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffe0004f0026-ffffffe0004f0122: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
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
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815abc20)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815abc20-ffffffff815abd04: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159adc0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff8159adc0-ffffffff8159aea4: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ac1b0)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815ac1b0-ffffffff815ac294: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t hdmi_vendor_infoframe_pack_only(const struct hdmi_vendor_infoframe *frame, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c5b40)
Location: drivers/video/hdmi.c:567
Inline: True
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_pack_only
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815c5b40-ffffffff815c5c24: hdmi_vendor_infoframe_pack_only (STB_GLOBAL)
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

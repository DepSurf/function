# Function: <code>usb_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816119e0)
Location: drivers/usb/core/message.c:812
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff816119e0-ffffffff81611bee: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81671940)
Location: drivers/usb/core/message.c:809
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81671940-ffffffff81671b4f: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169f5f0)
Location: drivers/usb/core/message.c:812
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff8169f5f0-ffffffff8169f7ff: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b4810)
Location: drivers/usb/core/message.c:810
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff816b4810-ffffffff816b4a20: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171fcd0)
Location: drivers/usb/core/message.c:814
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff8171fcd0-ffffffff8171fee0: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175e640)
Location: drivers/usb/core/message.c:815
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff8175e640-ffffffff8175e83d: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81782dc0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81782dc0-ffffffff81782fbd: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff817c3595-ffffffff817c35ed: usb_string.cold (STB_LOCAL)
ffffffff817c1520-ffffffff817c16c3: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff817f3f15-ffffffff817f3f6d: usb_string.cold (STB_LOCAL)
ffffffff817f1ea0-ffffffff817f2043: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:824
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff818c3a96-ffffffff818c3aee: usb_string.cold (STB_LOCAL)
ffffffff818c1820-ffffffff818c19c3: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:961
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81c1d053-ffffffff81c1d0ab: usb_string.cold (STB_LOCAL)
ffffffff818cdaf0-ffffffff818cdc93: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:967
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81c0ef19-ffffffff81c0ef71: usb_string.cold (STB_LOCAL)
ffffffff818b1130-ffffffff818b12d3: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:967
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81d160b9-ffffffff81d16111: usb_string.cold (STB_LOCAL)
ffffffff81946390-ffffffff8194652d: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:967
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81ee0c70-ffffffff81ee0cc8: usb_string.cold (STB_LOCAL)
ffffffff81a9eb40-ffffffff81a9ed00: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c23cf0)
Location: drivers/usb/core/message.c:967
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81c23cf0-ffffffff81c23f0b: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8ac60)
Location: drivers/usb/core/message.c:967
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81c8ac60-ffffffff81c8ae7b: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3f680)
Location: drivers/usb/core/message.c:968
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81d3f680-ffffffff81d3f8c6: usb_string (STB_GLOBAL)
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
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a22208)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffff800010a22208-ffff800010a22418: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af8fb8)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
c0af8fb8-c0af91c8: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adcbd0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
c000000000adcbd0-c000000000adce84: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000644f12)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffe000644f12-ffffffe0006450f8: usb_string (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff817ac2f5-ffffffff817ac34d: usb_string.cold (STB_LOCAL)
ffffffff817aa280-ffffffff817aa423: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff8179dcf5-ffffffff8179dd4d: usb_string.cold (STB_LOCAL)
ffffffff8179bc80-ffffffff8179be23: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff817e8d95-ffffffff817e8ded: usb_string.cold (STB_LOCAL)
ffffffff817e6d20-ffffffff817e6ec3: usb_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_string(struct usb_device *dev, int index, char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:816
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_cache_string
```
**Symbols:**

```
ffffffff81802fe5-ffffffff8180303d: usb_string.cold (STB_LOCAL)
ffffffff818010e0-ffffffff81801283: usb_string (STB_GLOBAL)
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

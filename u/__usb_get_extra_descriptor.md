# Function: <code>__usb_get_extra_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81602fe0)
Location: drivers/usb/core/usb.c:678
Inline: False
```
**Symbols:**

```
ffffffff81602fe0-ffffffff81603048: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81662ca0)
Location: drivers/usb/core/usb.c:683
Inline: False
```
**Symbols:**

```
ffffffff81662ca0-ffffffff81662d06: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81690a90)
Location: drivers/usb/core/usb.c:697
Inline: False
```
**Symbols:**

```
ffffffff81690a90-ffffffff81690af6: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a6010)
Location: drivers/usb/core/usb.c:833
Inline: False
```
**Symbols:**

```
ffffffff816a6010-ffffffff816a6086: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817113e0)
Location: drivers/usb/core/usb.c:833
Inline: False
```
**Symbols:**

```
ffffffff817113e0-ffffffff81711456: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:834
Inline: False
```
**Symbols:**

```
ffffffff81750ac7-ffffffff81750ae9: __usb_get_extra_descriptor.cold.14 (STB_LOCAL)
ffffffff81750130-ffffffff8175018d: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:834
Inline: False
```
**Symbols:**

```
ffffffff81774f18-ffffffff81774f44: __usb_get_extra_descriptor.cold.14 (STB_LOCAL)
ffffffff81774560-ffffffff817745ca: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff817b3044-ffffffff817b306a: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff817b2680-ffffffff817b26d6: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff817e3774-ffffffff817e379a: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff817e2db0-ffffffff817e2e06: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff818b22cb-ffffffff818b22e9: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff818b1900-ffffffff818b1958: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:872
Inline: False
```
**Symbols:**

```
ffffffff81c1a7e2-ffffffff81c1a800: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff818c02b0-ffffffff818c0308: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:918
Inline: False
```
**Symbols:**

```
ffffffff81c0c6ce-ffffffff81c0c6f5: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff818a34a0-ffffffff818a34f0: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:918
Inline: False
```
**Symbols:**

```
ffffffff81d135df-ffffffff81d13606: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff81938060-ffffffff819380b0: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:880
Inline: False
```
**Symbols:**

```
ffffffff81ede3b4-ffffffff81ede3f0: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff81a8f940-ffffffff81a8f9b4: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11670)
Location: drivers/usb/core/usb.c:880
Inline: False
```
**Symbols:**

```
ffffffff81c11670-ffffffff81c11713: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c78430)
Location: drivers/usb/core/usb.c:956
Inline: False
```
**Symbols:**

```
ffffffff81c78430-ffffffff81c784d3: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2ce30)
Location: drivers/usb/core/usb.c:944
Inline: False
```
**Symbols:**

```
ffffffff81d2ce30-ffffffff81d2ced3: __usb_get_extra_descriptor (STB_GLOBAL)
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
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a11158)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffff800010a11158-ffff800010a11224: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0ae9804)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
c0ae9804-c0ae9894: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac80d0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
c000000000ac80d0-c000000000ac8188: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe000636d4a)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffe000636d4a-ffffffe000636dd6: __usb_get_extra_descriptor (STB_GLOBAL)
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
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff8179bb54-ffffffff8179bb7a: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff8179b190-ffffffff8179b1e6: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff8178d7e4-ffffffff8178d80a: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff8178ce20-ffffffff8178ce76: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff817d85f4-ffffffff817d861a: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff817d7c30-ffffffff817d7c86: __usb_get_extra_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __usb_get_extra_descriptor(char *buffer, unsigned int size, unsigned char type, void **ptr, size_t minsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:853
Inline: False
```
**Symbols:**

```
ffffffff817f2894-ffffffff817f28ba: __usb_get_extra_descriptor.cold (STB_LOCAL)
ffffffff817f1ed0-ffffffff817f1f26: __usb_get_extra_descriptor (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t minsize</code>
</li>
</ul>
</details>
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

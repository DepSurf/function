# Function: <code>usb_sg_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81611850)
Location: drivers/usb/core/message.c:578
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81611850-ffffffff8161191c: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81671440)
Location: drivers/usb/core/message.c:578
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81671440-ffffffff81671511: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169f0f0)
Location: drivers/usb/core/message.c:581
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff8169f0f0-ffffffff8169f1c1: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b4300)
Location: drivers/usb/core/message.c:579
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff816b4300-ffffffff816b43eb: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171fb30)
Location: drivers/usb/core/message.c:583
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff8171fb30-ffffffff8171fc1b: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175e490)
Location: drivers/usb/core/message.c:584
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff8175e490-ffffffff8175e57a: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81782c10)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81782c10-ffffffff81782cfa: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff817c3471-ffffffff817c3496: usb_sg_cancel.cold (STB_LOCAL)
ffffffff817c1060-ffffffff817c1111: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff817f3df1-ffffffff817f3e16: usb_sg_cancel.cold (STB_LOCAL)
ffffffff817f19e0-ffffffff817f1a91: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:586
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff818c3971-ffffffff818c3997: usb_sg_cancel.cold (STB_LOCAL)
ffffffff818c1320-ffffffff818c1412: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81c1cf2e-ffffffff81c1cf54: usb_sg_cancel.cold (STB_LOCAL)
ffffffff818cd5d0-ffffffff818cd6c2: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81c0edf4-ffffffff81c0ee1a: usb_sg_cancel.cold (STB_LOCAL)
ffffffff818b0bf0-ffffffff818b0ce3: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81d15f94-ffffffff81d15fba: usb_sg_cancel.cold (STB_LOCAL)
ffffffff81945e50-ffffffff81945f43: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81ee0b3f-ffffffff81ee0b65: usb_sg_cancel.cold (STB_LOCAL)
ffffffff81a9e5c0-ffffffff81a9e6c1: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c23680)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81c23680-ffffffff81c237a5: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8a600)
Location: drivers/usb/core/message.c:720
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81c8a600-ffffffff81c8a725: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3f020)
Location: drivers/usb/core/message.c:721
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81d3f020-ffffffff81d3f145: usb_sg_cancel (STB_GLOBAL)
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
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a22eb0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffff800010a22eb0-ffff800010a23018: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af88dc)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
c0af88dc-c0af89b8: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adc460)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
c000000000adc460-c000000000adc5e0: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe0006449a4)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffe0006449a4-ffffffe000644aae: usb_sg_cancel (STB_GLOBAL)
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
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff817ac1d1-ffffffff817ac1f6: usb_sg_cancel.cold (STB_LOCAL)
ffffffff817a9dc0-ffffffff817a9e71: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff8179dbd1-ffffffff8179dbf6: usb_sg_cancel.cold (STB_LOCAL)
ffffffff8179b7c0-ffffffff8179b871: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff817e8c71-ffffffff817e8c96: usb_sg_cancel.cold (STB_LOCAL)
ffffffff817e6860-ffffffff817e6911: usb_sg_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void usb_sg_cancel(struct usb_sg_request *io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:585
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81802ec1-ffffffff81802ee6: usb_sg_cancel.cold (STB_LOCAL)
ffffffff81800ac0-ffffffff81800b71: usb_sg_cancel (STB_GLOBAL)
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

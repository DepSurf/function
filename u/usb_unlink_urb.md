# Function: <code>usb_unlink_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81610000)
Location: drivers/usb/core/urb.c:621
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81610000-ffffffff8161003a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8166fbd0)
Location: drivers/usb/core/urb.c:621
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8166fbd0-ffffffff8166fc0a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169d8a0)
Location: drivers/usb/core/urb.c:621
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8169d8a0-ffffffff8169d8da: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816b2c60)
Location: drivers/usb/core/urb.c:621
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff816b2c60-ffffffff816b2c9a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171e320)
Location: drivers/usb/core/urb.c:644
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8171e320-ffffffff8171e35a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175d560)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8175d560-ffffffff8175d59a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81781ba0)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81781ba0-ffffffff81781bda: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817c00f0)
Location: drivers/usb/core/urb.c:648
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817c00f0-ffffffff817c012a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f0a70)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817f0a70-ffffffff817f0aaa: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818c09f7)
Location: drivers/usb/core/urb.c:649
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:cancel_bulk_urbs
```
**Symbols:**

```
ffffffff818bff80-ffffffff818bffba: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cc2ec)
Location: drivers/usb/core/urb.c:664
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:cancel_bulk_urbs
```
**Symbols:**

```
ffffffff818cba40-ffffffff818cba7a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818af7fc)
Location: drivers/usb/core/urb.c:664
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818af060-ffffffff818af09a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8194494c)
Location: drivers/usb/core/urb.c:673
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff819441b0-ffffffff819441ea: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81a9d106)
Location: drivers/usb/core/urb.c:673
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81a9c6f0-ffffffff81a9c74a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c22196)
Location: drivers/usb/core/urb.c:675
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81c21680-ffffffff81c216da: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c89106)
Location: drivers/usb/core/urb.c:675
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81c88600-ffffffff81c8865a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81d3db56)
Location: drivers/usb/core/urb.c:660
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81d3d050-ffffffff81d3d0aa: usb_unlink_urb (STB_GLOBAL)
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
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a205f8)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffff800010a205f8-ffff800010a20654: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c0af77c4)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c0af77c4-c0af781c: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000adaa70)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c000000000adaa70-c000000000adaae0: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe0006438c4)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffe0006438c4-ffffffe00064390a: usb_unlink_urb (STB_GLOBAL)
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
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a8e50)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817a8e50-ffffffff817a8e8a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a860)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8179a860-ffffffff8179a89a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e58f0)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817e58f0-ffffffff817e592a: usb_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_unlink_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817ffb50)
Location: drivers/usb/core/urb.c:649
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817ffb50-ffffffff817ffb8a: usb_unlink_urb (STB_GLOBAL)
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

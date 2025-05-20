# Function: <code>clear_hub_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603c10)
Location: drivers/usb/core/hub.c:387
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81603c10-ffffffff81603c59: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816638f0)
Location: drivers/usb/core/hub.c:389
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816638f0-ffffffff81663939: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816916f0)
Location: drivers/usb/core/hub.c:392
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816916f0-ffffffff81691739: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a6c50)
Location: drivers/usb/core/hub.c:401
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816a6c50-ffffffff816a6c85: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712020)
Location: drivers/usb/core/hub.c:401
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81712020-ffffffff81712055: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81750d90)
Location: drivers/usb/core/hub.c:404
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81750d90-ffffffff81750dc5: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817751f0)
Location: drivers/usb/core/hub.c:405
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817751f0-ffffffff81775225: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b3370)
Location: drivers/usb/core/hub.c:407
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817b3370-ffffffff817b33a9: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e3aa0)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817e3aa0-ffffffff817e3ad9: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b9879)
Location: drivers/usb/core/hub.c:411
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c8159)
Location: drivers/usb/core/hub.c:411
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818ab7c3)
Location: drivers/usb/core/hub.c:418
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81940743)
Location: drivers/usb/core/hub.c:418
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a98901)
Location: drivers/usb/core/hub.c:418
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1b7c0)
Location: drivers/usb/core/hub.c:422
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c826e5)
Location: drivers/usb/core/hub.c:422
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d37025)
Location: drivers/usb/core/hub.c:442
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
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
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a121c8)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffff800010a121c8-ffff800010a1222c: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aea6c8)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
c0aea6c8-c0aea720: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9590)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
c000000000ac9590-c000000000ac95f0: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000637bce)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffe000637bce-ffffffe000637c28: clear_hub_feature (STB_LOCAL)
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
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179be80)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8179be80-ffffffff8179beb9: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178db10)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8178db10-ffffffff8178db49: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d8920)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817d8920-ffffffff817d8959: clear_hub_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clear_hub_feature(struct usb_device *hdev, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f2c90)
Location: drivers/usb/core/hub.c:409
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817f2c90-ffffffff817f2cc9: clear_hub_feature (STB_LOCAL)
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

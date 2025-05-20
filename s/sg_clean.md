# Function: <code>sg_clean</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81610d10)
Location: drivers/usb/core/message.c:253
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_wait
```
**Symbols:**

```
ffffffff81610d10-ffffffff81610d67: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81670920)
Location: drivers/usb/core/message.c:254
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff81670920-ffffffff81670977: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169e5d0)
Location: drivers/usb/core/message.c:257
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff8169e5d0-ffffffff8169e627: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b37d0)
Location: drivers/usb/core/message.c:254
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff816b37d0-ffffffff816b3827: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171ef80)
Location: drivers/usb/core/message.c:258
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff8171ef80-ffffffff8171efd7: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175dd10)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff8175dd10-ffffffff8175dd67: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817822e0)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff817822e0-ffffffff81782337: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c07a0)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff817c07a0-ffffffff817c07f7: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f1120)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff817f1120-ffffffff817f1177: sg_clean (STB_LOCAL)
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
In drivers/usb/core/message.c (ffffffff818c1e6f)
Location: drivers/usb/core/message.c:260
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff818ce07f)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff818b1a7e)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff81946cce)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff81a9f121)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff81c24591)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff81c8b5e1)
Location: drivers/usb/core/message.c:393
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
In drivers/usb/core/message.c (ffffffff81d40091)
Location: drivers/usb/core/message.c:394
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
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
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a21578)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffff800010a21578-ffff800010a215e4: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af7f54)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
c0af7f54-c0af7fc4: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adb610)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
c000000000adb610-c000000000adb6b8: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe00064411c)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffe00064411c-ffffffe000644174: sg_clean (STB_LOCAL)
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
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817a9500)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff817a9500-ffffffff817a9557: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179af00)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff8179af00-ffffffff8179af57: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e5fa0)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff817e5fa0-ffffffff817e5ff7: sg_clean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sg_clean(struct usb_sg_request *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81800200)
Location: drivers/usb/core/message.c:259
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
```
**Symbols:**

```
ffffffff81800200-ffffffff81800257: sg_clean (STB_LOCAL)
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

# Function: <code>snoop_urb_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161b280)
Location: drivers/usb/core/devio.c:401
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8161b280-ffffffff8161b3b7: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167a050)
Location: drivers/usb/core/devio.c:510
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8167a050-ffffffff8167a174: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a7d20)
Location: drivers/usb/core/devio.c:510
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff816a7d20-ffffffff816a7e3d: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bcf00)
Location: drivers/usb/core/devio.c:504
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff816bcf00-ffffffff816bd00e: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817288d0)
Location: drivers/usb/core/devio.c:494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817288d0-ffffffff817289de: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81767720)
Location: drivers/usb/core/devio.c:492
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81767720-ffffffff8176782a: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178c0a0)
Location: drivers/usb/core/devio.c:492
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8178c0a0-ffffffff8178c1aa: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817ca490)
Location: drivers/usb/core/devio.c:490
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817ca490-ffffffff817ca594: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817fb020)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817fb020-ffffffff817fb124: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818caf20)
Location: drivers/usb/core/devio.c:511
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818caf20-ffffffff818cb025: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d6010)
Location: drivers/usb/core/devio.c:511
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818d6010-ffffffff818d6115: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818b9550)
Location: drivers/usb/core/devio.c:511
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818b9550-ffffffff818b9648: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:512
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8194f380-ffffffff8194f487: snoop_urb_data (STB_LOCAL)
ffffffff81d16f82-ffffffff81d16f97: snoop_urb_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:524
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81aa87b0-ffffffff81aa88cb: snoop_urb_data (STB_LOCAL)
ffffffff81ee1ece-ffffffff81ee1ee3: snoop_urb_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:524
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81c2fa30-ffffffff81c2fb4b: snoop_urb_data (STB_LOCAL)
ffffffff8209e9f1-ffffffff8209ea06: snoop_urb_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:531
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81c96cb0-ffffffff81c96dd0: snoop_urb_data (STB_LOCAL)
ffffffff8211ff7f-ffffffff8211ff93: snoop_urb_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:531
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81d4b790-ffffffff81d4b8b0: snoop_urb_data (STB_LOCAL)
ffffffff82201755-ffffffff82201769: snoop_urb_data.cold (STB_LOCAL)
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
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2bf60)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffff800010a2bf60-ffff800010a2c0b0: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b0236c)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c0b0236c-c0b024a8: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000ae9dd0)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c000000000ae9dd0-c000000000ae9f84: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064de4e)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffe00064de4e-ffffffe00064df70: snoop_urb_data (STB_LOCAL)
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
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817b3400)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817b3400-ffffffff817b3504: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817a4e30)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817a4e30-ffffffff817a4f34: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817efea0)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff817efea0-ffffffff817effa4: snoop_urb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void snoop_urb_data(struct urb *urb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8180a0e0)
Location: drivers/usb/core/devio.c:502
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8180a0e0-ffffffff8180a1e4: snoop_urb_data (STB_LOCAL)
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

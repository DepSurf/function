# Function: <code>check_ctrlrecip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161aae0)
Location: drivers/usb/core/devio.c:714
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8161aae0-ffffffff8161ac17: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167a700)
Location: drivers/usb/core/devio.c:828
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8167a700-ffffffff8167a834: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a83c0)
Location: drivers/usb/core/devio.c:828
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff816a83c0-ffffffff816a84f4: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bd930)
Location: drivers/usb/core/devio.c:822
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff816bd930-ffffffff816bda67: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81729300)
Location: drivers/usb/core/devio.c:812
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff81729300-ffffffff81729437: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81767db0)
Location: drivers/usb/core/devio.c:808
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff81767db0-ffffffff81767ef6: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178c600)
Location: drivers/usb/core/devio.c:809
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8178c600-ffffffff8178c746: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:804
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817caa20-ffffffff817cab16: check_ctrlrecip (STB_LOCAL)
ffffffff817cdf22-ffffffff817cdf67: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817fb5f0-ffffffff817fb6e6: check_ctrlrecip (STB_LOCAL)
ffffffff817fed12-ffffffff817fed57: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:856
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff818cba00-ffffffff818cbaf3: check_ctrlrecip (STB_LOCAL)
ffffffff818cf31e-ffffffff818cf35f: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:856
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff818d6cf0-ffffffff818d6de3: check_ctrlrecip (STB_LOCAL)
ffffffff81c1e20c-ffffffff81c1e24d: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:856
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff818b9db0-ffffffff818b9ea3: check_ctrlrecip (STB_LOCAL)
ffffffff81c10033-ffffffff81c10074: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:857
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff8194fa60-ffffffff8194fb48: check_ctrlrecip (STB_LOCAL)
ffffffff81d17127-ffffffff81d1716c: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:869
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81aa8d20-ffffffff81aa8e23: check_ctrlrecip (STB_LOCAL)
ffffffff81ee1f9b-ffffffff81ee1fe0: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c2f8d0)
Location: drivers/usb/core/devio.c:869
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81c2f8d0-ffffffff81c2fa13: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c96b50)
Location: drivers/usb/core/devio.c:878
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81c96b50-ffffffff81c96c93: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4b630)
Location: drivers/usb/core/devio.c:878
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81d4b630-ffffffff81d4b773: check_ctrlrecip (STB_LOCAL)
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
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2c8a8)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffff800010a2c8a8-ffff800010a2ca24: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b0222c)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
c0b0222c-c0b0236c: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000ae9ae0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
c000000000ae9ae0-c000000000ae9d0c: check_ctrlrecip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064dd28)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffe00064dd28-ffffffe00064de4e: check_ctrlrecip (STB_LOCAL)
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
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817b39d0-ffffffff817b3ac6: check_ctrlrecip (STB_LOCAL)
ffffffff817b70f2-ffffffff817b7137: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817a5400-ffffffff817a54f6: check_ctrlrecip (STB_LOCAL)
ffffffff817a8b12-ffffffff817a8b57: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817f0470-ffffffff817f0566: check_ctrlrecip (STB_LOCAL)
ffffffff817f3b92-ffffffff817f3bd7: check_ctrlrecip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_ctrlrecip(struct usb_dev_state *ps, unsigned int requesttype, unsigned int request, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:847
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8180a6b0-ffffffff8180a7a6: check_ctrlrecip (STB_LOCAL)
ffffffff8180de12-ffffffff8180de57: check_ctrlrecip.cold (STB_LOCAL)
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

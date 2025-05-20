# Function: <code>rtc_update_hrtimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81673e90)
Location: drivers/rtc/interface.c:644
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81673e90-ffffffff81673ef9: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d4680)
Location: drivers/rtc/interface.c:652
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff816d4680-ffffffff816d46df: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704360)
Location: drivers/rtc/interface.c:652
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81704360-ffffffff817043bf: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81719f40)
Location: drivers/rtc/interface.c:659
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81719f40-ffffffff81719f9f: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178b1b0)
Location: drivers/rtc/interface.c:659
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff8178b1b0-ffffffff8178b20f: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cc9c0)
Location: drivers/rtc/interface.c:757
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff817cc9c0-ffffffff817cca28: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f3cc0)
Location: drivers/rtc/interface.c:711
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff817f3cc0-ffffffff817f3d28: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81834a00)
Location: drivers/rtc/interface.c:702
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81834a00-ffffffff81834a6e: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81866320)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81866320-ffffffff8186638e: rtc_update_hrtimer (STB_LOCAL)
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
In drivers/rtc/interface.c (ffffffff8193b889)
Location: drivers/rtc/interface.c:724
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81941bc9)
Location: drivers/rtc/interface.c:724
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81925359)
Location: drivers/rtc/interface.c:710
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff819c82e9)
Location: drivers/rtc/interface.c:710
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81b290f9)
Location: drivers/rtc/interface.c:721
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81cbcc79)
Location: drivers/rtc/interface.c:721
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81d24589)
Location: drivers/rtc/interface.c:721
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
In drivers/rtc/interface.c (ffffffff81dda2e9)
Location: drivers/rtc/interface.c:721
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
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
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa7750)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffff800010aa7750-ffff800010aa77d8: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b86948)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
c0b86948-c0b869dc: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b894e0)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
c000000000b894e0-c000000000b895a0: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3890)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffe0006b3890-ffffffe0006b3904: rtc_update_hrtimer (STB_LOCAL)
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
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81818fd0)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81818fd0-ffffffff8181903e: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e06c0)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff817e06c0-ffffffff817e072e: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185a4b0)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff8185a4b0-ffffffff8185a51e: rtc_update_hrtimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtc_update_hrtimer(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875590)
Location: drivers/rtc/interface.c:710
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
**Symbols:**

```
ffffffff81875590-ffffffff818755fe: rtc_update_hrtimer (STB_LOCAL)
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

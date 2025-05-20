# Function: <code>__tasklet_hi_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085470)
Location: kernel/softirq.c:462
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff81085470-ffffffff8108552c: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088550)
Location: kernel/softirq.c:462
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff81088550-ffffffff81088605: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d580)
Location: kernel/softirq.c:476
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff8108d580-ffffffff8108d636: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a4f0)
Location: kernel/softirq.c:476
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff8108a4f0-ffffffff8108a5a6: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81091080)
Location: kernel/softirq.c:476
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff81091080-ffffffff81091139: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094d4a)
Location: kernel/softirq.c:493
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff81094d10-ffffffff81094d29: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d15a)
Location: kernel/softirq.c:494
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff8109d120-ffffffff8109d139: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1800)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810a1800-ffffffff810a1819: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7dc0)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810a7dc0-ffffffff810a7dd9: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af480)
Location: kernel/softirq.c:521
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810af480-ffffffff810af541: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aac20)
Location: kernel/softirq.c:525
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810aac20-ffffffff810aacd1: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810abfb0)
Location: kernel/softirq.c:742
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810abfb0-ffffffff810ac069: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bdc30)
Location: kernel/softirq.c:741
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810bdc30-ffffffff810bdcb0: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4d20)
Location: kernel/softirq.c:755
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
**Symbols:**

```
ffffffff810d4d20-ffffffff810d4d43: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3d60)
Location: kernel/softirq.c:755
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
**Symbols:**

```
ffffffff810f3d60-ffffffff810f3d83: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81100190)
Location: kernel/softirq.c:737
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
**Symbols:**

```
ffffffff81100190-ffffffff811001b3: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811098b0)
Location: kernel/softirq.c:737
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
**Symbols:**

```
ffffffff811098b0-ffffffff811098d3: __tasklet_hi_schedule (STB_GLOBAL)
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
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff660)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffff8000100ff660-ffff8000100ff69c: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035c278)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
c035c278-c035c2a0: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000146a20)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
c000000000146a20-c000000000146a40: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c7482)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffe0000c7482-ffffffe0000c74b6: __tasklet_hi_schedule (STB_GLOBAL)
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
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a16e0)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810a16e0-ffffffff810a16f9: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810900c0)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810900c0-ffffffff810900d9: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1690)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810a1690-ffffffff810a16a9: __tasklet_hi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a9650)
Location: kernel/softirq.c:494
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
**Symbols:**

```
ffffffff810a9650-ffffffff810a9669: __tasklet_hi_schedule (STB_GLOBAL)
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

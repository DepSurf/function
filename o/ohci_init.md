# Function: <code>ohci_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81641330)
Location: drivers/usb/host/ohci-hcd.c:441
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_restart
```
**Symbols:**

```
ffffffff81641330-ffffffff8164175d: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1e40)
Location: drivers/usb/host/ohci-hcd.c:441
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff816a1e40-ffffffff816a2247: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0ac0)
Location: drivers/usb/host/ohci-hcd.c:441
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff816d0ac0-ffffffff816d0ec7: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e5120)
Location: drivers/usb/host/ohci-hcd.c:442
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff816e5120-ffffffff816e5552: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81751940)
Location: drivers/usb/host/ohci-hcd.c:444
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81751940-ffffffff81751d75: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81791410)
Location: drivers/usb/host/ohci-hcd.c:444
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81791410-ffffffff817917da: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b7bb0)
Location: drivers/usb/host/ohci-hcd.c:444
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff817b7bb0-ffffffff817b7ec1: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff817f6490-ffffffff817f67bc: ohci_init (STB_LOCAL)
ffffffff817f9a50-ffffffff817f9a6d: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff818272f0-ffffffff8182761c: ohci_init (STB_LOCAL)
ffffffff8182a88a-ffffffff8182a8a7: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff818fa000-ffffffff818fa333: ohci_init (STB_LOCAL)
ffffffff818fc6ec-ffffffff818fc709: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81902b40-ffffffff81902e73: ohci_init (STB_LOCAL)
ffffffff81c204b2-ffffffff81c204cf: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff818e5c80-ffffffff818e5fbf: ohci_init (STB_LOCAL)
ffffffff81c12518-ffffffff81c12535: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81982020-ffffffff8198237a: ohci_init (STB_LOCAL)
ffffffff81d1ef6c-ffffffff81d1efb7: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:452
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81adf030-ffffffff81adf386: ohci_init (STB_LOCAL)
ffffffff81eeabab-ffffffff81eeabf6: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:452
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81c6a590-ffffffff81c6a8ff: ohci_init (STB_LOCAL)
ffffffff820a54e0-ffffffff820a550e: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:452
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81cd1980-ffffffff81cd1ce9: ohci_init (STB_LOCAL)
ffffffff82126a06-ffffffff82126a34: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:452
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81d86940-ffffffff81d86ca9: ohci_init (STB_LOCAL)
ffffffff82208209-ffffffff82208237: ohci_init.cold (STB_LOCAL)
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
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a62230)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffff800010a62230-ffff800010a625c8: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b353e0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_tmio_start
  - drivers/usb/host/ohci-hcd.c:ohci_sm501_init
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
c0b353e0-c0b35670: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b31ba0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
c000000000b31ba0-c000000000b32178: ohci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe00067d482)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffe00067d482-ffffffe00067d838: ohci_init (STB_LOCAL)
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
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff817df6d0-ffffffff817df9fc: ohci_init (STB_LOCAL)
ffffffff817e2c6a-ffffffff817e2c87: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff8181c170-ffffffff8181c49c: ohci_init (STB_LOCAL)
ffffffff8181f70a-ffffffff8181f727: ohci_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ohci_init(struct ohci_hcd *ohci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_setup
```
**Symbols:**

```
ffffffff81837050-ffffffff8183737c: ohci_init (STB_LOCAL)
ffffffff81839779-ffffffff81839796: ohci_init.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

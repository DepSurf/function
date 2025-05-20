# Function: <code>dwc2_host_enter_hibernation</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81779780)
Location: drivers/usb/dwc2/hcd.c:5495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81779780-ffffffff817799c4: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179f5f0)
Location: drivers/usb/dwc2/hcd.c:5514
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff8179f5f0-ffffffff8179f947: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff817dedd6-ffffffff817dee20: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff817de140-ffffffff817de42d: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff8180fcc8-ffffffff8180fd12: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff8180f090-ffffffff8180f37d: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff818e09b3-ffffffff818e09fd: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff818dfda0-ffffffff818e008a: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5372
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81c1fa2a-ffffffff81c1fa74: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff818e9c00-ffffffff818e9eea: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5489
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81c11678-ffffffff81c116c2: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff818cb6e0-ffffffff818cb9eb: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5494
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81d1c09a-ffffffff81d1c3f1: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81964b70-ffffffff81965086: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5490
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81ee74dd-ffffffff81ee793b: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81abf090-ffffffff81abf49a: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5463
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff820a2c0a-ffffffff820a3009: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81c48950-ffffffff81c48db2: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5463
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff821241be-ffffffff821245bd: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81caff30-ffffffff81cb0392: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5463
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff82205992-ffffffff82205d91: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81d64c40-ffffffff81d650a2: dwc2_host_enter_hibernation (STB_GLOBAL)
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
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a47cb8)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffff800010a47cb8-ffff800010a4811c: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b1a408)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
c0b1a408-c0b1a850: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b0cbf0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
c000000000b0cbf0-c000000000b0d430: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe0006648ca)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffe0006648ca-ffffffe000664f96: dwc2_host_enter_hibernation (STB_GLOBAL)
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
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff817c80a8-ffffffff817c80f2: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff817c7470-ffffffff817c775d: dwc2_host_enter_hibernation (STB_GLOBAL)
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
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff81804b48-ffffffff81804b92: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff81803f10-ffffffff818041fd: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_host_enter_hibernation(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5370
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff8181ec58-ffffffff8181eca2: dwc2_host_enter_hibernation.cold (STB_LOCAL)
ffffffff8181e020-ffffffff8181e30d: dwc2_host_enter_hibernation (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

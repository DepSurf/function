# Function: <code>dwc2_check_params</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff816c6bad)
Location: drivers/usb/dwc2/params.c:502
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81732fa1)
Location: drivers/usb/dwc2/params.c:516
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81772430)
Location: drivers/usb/dwc2/params.c:575
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81772430-ffffffff81772e30: dwc2_check_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81797560)
Location: drivers/usb/dwc2/params.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81797560-ffffffff81797fa2: dwc2_check_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:619
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff817d6640-ffffffff817d6bd4: dwc2_check_params (STB_LOCAL)
ffffffff817d727d-ffffffff817d78a0: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff818074d0-ffffffff81807a64: dwc2_check_params (STB_LOCAL)
ffffffff8180810d-ffffffff81808730: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:649
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff818d8120-ffffffff818d8634: dwc2_check_params (STB_LOCAL)
ffffffff818d8c63-ffffffff818d921f: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:650
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff818e2620-ffffffff818e2b34: dwc2_check_params (STB_LOCAL)
ffffffff81c1eeff-ffffffff81c1f4bb: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:665
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff818c5980-ffffffff818c5e59: dwc2_check_params (STB_LOCAL)
ffffffff81c10da7-ffffffff81c11363: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:665
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff8195d900-ffffffff8195defb: dwc2_check_params (STB_LOCAL)
ffffffff81d19b82-ffffffff81d1a610: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:732
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81ab7b50-ffffffff81ab8227: dwc2_check_params (STB_LOCAL)
ffffffff81ee4c55-ffffffff81ee5735: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:706
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81c40790-ffffffff81c41469: dwc2_check_params (STB_LOCAL)
ffffffff820a0c46-ffffffff820a119e: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:726
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81ca7d60-ffffffff81ca8a31: dwc2_check_params (STB_LOCAL)
ffffffff82122219-ffffffff82122771: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:757
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81d5c9f0-ffffffff81d5d6c1: dwc2_check_params (STB_LOCAL)
ffffffff822039f0-ffffffff82203f48: dwc2_check_params.cold (STB_LOCAL)
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
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffff800010a3ede8)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffff800010a3ede8-ffff800010a3f840: dwc2_check_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c0b11940)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
c0b11940-c0b12438: dwc2_check_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c000000000afee60)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
c000000000afee60-c000000000affcd4: dwc2_check_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffe00065aba6)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffe00065aba6-ffffffe00065b4ec: dwc2_check_params (STB_LOCAL)
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
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff817bf8b0-ffffffff817bfe44: dwc2_check_params (STB_LOCAL)
ffffffff817c04ed-ffffffff817c0b10: dwc2_check_params.cold (STB_LOCAL)
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
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff817fc350-ffffffff817fc8e4: dwc2_check_params (STB_LOCAL)
ffffffff817fcf8d-ffffffff817fd5b0: dwc2_check_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_check_params(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/params.c (0)
Location: drivers/usb/dwc2/params.c:616
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81816460-ffffffff818169f4: dwc2_check_params (STB_LOCAL)
ffffffff8181709d-ffffffff818176c0: dwc2_check_params.cold (STB_LOCAL)
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

# Function: <code>dwc2_set_param_tx_fifo_sizes</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff816b2470)
Location: drivers/usb/dwc2/params.c:1047
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_parameters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff816c66b0)
Location: drivers/usb/dwc2/params.c:228
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff816c66b0-ffffffff816c66e9: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81732a70)
Location: drivers/usb/dwc2/params.c:240
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81732a70-ffffffff81732aaf: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff817723f0)
Location: drivers/usb/dwc2/params.c:241
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff817723f0-ffffffff8177242f: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81797520)
Location: drivers/usb/dwc2/params.c:247
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff81797520-ffffffff8179755f: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff817d6600)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff817d6600-ffffffff817d6639: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81807490)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff81807490-ffffffff818074c9: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
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
In drivers/usb/dwc2/params.c (ffffffff818d8fd9)
Location: drivers/usb/dwc2/params.c:302
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
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
In drivers/usb/dwc2/params.c (ffffffff81c1f275)
Location: drivers/usb/dwc2/params.c:303
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
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
In drivers/usb/dwc2/params.c (ffffffff818c6405)
Location: drivers/usb/dwc2/params.c:318
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff81d1a2a3)
Location: drivers/usb/dwc2/params.c:318
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81ab7b00)
Location: drivers/usb/dwc2/params.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
**Symbols:**

```
ffffffff81ab7b00-ffffffff81ab7b43: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81c40730)
Location: drivers/usb/dwc2/params.c:359
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
**Symbols:**

```
ffffffff81c40730-ffffffff81c40773: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81ca7d00)
Location: drivers/usb/dwc2/params.c:380
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
**Symbols:**

```
ffffffff81ca7d00-ffffffff81ca7d43: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81d5c990)
Location: drivers/usb/dwc2/params.c:411
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
**Symbols:**

```
ffffffff81d5c990-ffffffff81d5c9d3: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
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
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffff800010a3edb0)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffff800010a3edb0-ffff800010a3ede4: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c0b11918)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
c0b11918-c0b11940: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c000000000afee30)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
c000000000afee30-c000000000afee60: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffe00065bc0e)
Location: drivers/usb/dwc2/params.c:269
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff817bf870)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff817bf870-ffffffff817bf8a9: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff817fc310)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff817fc310-ffffffff817fc349: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_set_param_tx_fifo_sizes(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81816420)
Location: drivers/usb/dwc2/params.c:269
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
**Symbols:**

```
ffffffff81816420-ffffffff81816459: dwc2_set_param_tx_fifo_sizes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>ptp_disable_pinfunc</code>

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
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff817df4d0)
Location: drivers/ptp/ptp_chardev.c:29
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff817df4d0-ffffffff817df553: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff8180a8c0)
Location: drivers/ptp/ptp_chardev.c:31
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff8180a8c0-ffffffff8180a943: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff8184c5c0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff8184c5c0-ffffffff8184c648: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff8187ddc0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff8187ddc0-ffffffff8187de48: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff8194c250)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff8194c250-ffffffff8194c2c0: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81951c00)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81951c00-ffffffff81951c70: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81935a80)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81935a80-ffffffff81935af0: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff819d9170)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff819d9170-ffffffff819d91e3: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81b3c7a0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81b3c7a0-ffffffff81b3c827: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81cd2760)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81cd2760-ffffffff81cd27e7: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81d3a1e0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81d3a1e0-ffffffff81d3a267: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81df0790)
Location: drivers/ptp/ptp_chardev.c:19
Inline: True
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81df0790-ffffffff81df0817: ptp_disable_pinfunc.isra.0 (STB_LOCAL)
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
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffff800010ac76c0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffff800010ac76c0-ffff800010ac7794: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (c0ba70e0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
c0ba70e0-c0ba71b8: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (c000000000ba8f80)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
c000000000ba8f80-c000000000ba9084: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffe0006c6008)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffe0006c6008-ffffffe0006c60b6: ptp_disable_pinfunc (STB_LOCAL)
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
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81826330)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81826330-ffffffff818263b8: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff817ed9c0)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff817ed9c0-ffffffff817eda48: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff81873270)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff81873270-ffffffff818732f8: ptp_disable_pinfunc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptp_disable_pinfunc(struct ptp_clock_info *ops, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_chardev.c (ffffffff8188ec20)
Location: drivers/ptp/ptp_chardev.c:18
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
  - drivers/ptp/ptp_chardev.c:ptp_set_pinfunc
```
**Symbols:**

```
ffffffff8188ec20-ffffffff8188eca8: ptp_disable_pinfunc (STB_LOCAL)
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

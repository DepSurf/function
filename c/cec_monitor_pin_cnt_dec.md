# Function: <code>cec_monitor_pin_cnt_dec</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81806d10)
Location: drivers/media/cec/cec-adap.c:2057
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81806d10-ffffffff81806d42: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:2118
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81848e3a-ffffffff81848e4d: cec_monitor_pin_cnt_dec.cold (STB_LOCAL)
ffffffff81848550-ffffffff81848584: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81879e10)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81879e10-ffffffff81879e42: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac1b68)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010ac1b68-ffff800010ac1bbc: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba38a4)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba38a4-c0ba3908: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba4240)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba4240-c000000000ba42b0: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c2ee0)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c2ee0-ffffffe0006c2f20: cec_monitor_pin_cnt_dec (STB_GLOBAL)
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
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81822380)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81822380-ffffffff818223b2: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e9a20)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817e9a20-ffffffff817e9a52: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186f2c0)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186f2c0-ffffffff8186f2f2: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_monitor_pin_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81889240)
Location: drivers/media/cec/cec-adap.c:2135
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81889240-ffffffff81889272: cec_monitor_pin_cnt_dec (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

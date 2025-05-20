# Function: <code>__cec_s_log_addrs</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81806765)
Location: drivers/media/cec/cec-adap.c:1574
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8180738d-ffffffff818074e2: __cec_s_log_addrs.cold.18 (STB_LOCAL)
ffffffff81806730-ffffffff81806bd4: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81847fc5)
Location: drivers/media/cec/cec-adap.c:1635
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81848cc5-ffffffff81848e27: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff81847f90-ffffffff81848420: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81879885)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8187a4df-ffffffff8187a641: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff81879850-ffffffff81879ce0: __cec_s_log_addrs (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac1480)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010ac1480-ffff800010ac1a00: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba323c)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba323c-c0ba3740: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba3940)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba3940-c000000000ba400c: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c2962)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c2962-ffffffe0006c2dc2: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81821df5)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81822a4f-ffffffff81822bb1: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff81821dc0-ffffffff81822250: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e9495)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817ea0ef-ffffffff817ea251: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff817e9460-ffffffff817e98f0: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186ed35)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186f98f-ffffffff8186faf1: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff8186ed00-ffffffff8186f190: __cec_s_log_addrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __cec_s_log_addrs(struct cec_adapter *adap, struct cec_log_addrs *log_addrs, bool block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81888cb5)
Location: drivers/media/cec/cec-adap.c:1652
Inline: True
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_log_addrs
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8188990f-ffffffff81889a71: __cec_s_log_addrs.cold (STB_LOCAL)
ffffffff81888c80-ffffffff81889110: __cec_s_log_addrs (STB_GLOBAL)
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

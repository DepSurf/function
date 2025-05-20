# Function: <code>rtc_nvmem_register</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtc_nvmem_register(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8171b480)
Location: drivers/rtc/nvmem.c:87
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
```
**Symbols:**

```
ffffffff8171b480-ffffffff8171b55f: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtc_nvmem_register(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8178c720)
Location: drivers/rtc/nvmem.c:87
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
```
**Symbols:**

```
ffffffff8178c720-ffffffff8178c7ff: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817ced70)
Location: drivers/rtc/nvmem.c:85
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817ced70-ffffffff817cee60: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817f5ea0)
Location: drivers/rtc/nvmem.c:83
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817f5ea0-ffffffff817f5f77: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff81836b40)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81836b40-ffffffff81836c16: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff818684b0)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff818684b0-ffffffff81868586: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8193c0a0)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8193c0a0-ffffffff8193c176: rtc_nvmem_register (STB_GLOBAL)
```
</details>
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
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffff800010aaa250)
Location: drivers/rtc/nvmem.c:80
Inline: False
```
**Symbols:**

```
ffff800010aaa250-ffff800010aaa33c: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c0b8901c)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
**Symbols:**

```
c0b8901c-c0b89104: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c000000000b8c560)
Location: drivers/rtc/nvmem.c:80
Inline: False
```
**Symbols:**

```
c000000000b8c560-c000000000b8c6c0: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffe0006b5752)
Location: drivers/rtc/nvmem.c:80
Inline: False
```
**Symbols:**

```
ffffffe0006b5752-ffffffe0006b5822: rtc_nvmem_register (STB_GLOBAL)
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
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8181b160)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8181b160-ffffffff8181b236: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817e2850)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817e2850-ffffffff817e2926: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8185c640)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8185c640-ffffffff8185c716: rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff818778c0)
Location: drivers/rtc/nvmem.c:80
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff818778c0-ffffffff81877996: rtc_nvmem_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvmem_config *nvmem_config</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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

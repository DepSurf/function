# Function: <code>cec_monitor_all_cnt_dec</code>

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
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81806c80)
Location: drivers/media/cec/cec-adap.c:2034
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81806c80-ffffffff81806cb2: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:2095
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81848e27-ffffffff81848e3a: cec_monitor_all_cnt_dec.cold (STB_LOCAL)
ffffffff818484c0-ffffffff818484f4: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81879d80)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81879d80-ffffffff81879db2: cec_monitor_all_cnt_dec (STB_GLOBAL)
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
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac1ab8)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010ac1ab8-ffff800010ac1b0c: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba37e8)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba37e8-c0ba384c: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba4130)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba4130-c000000000ba41a0: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c2e5e)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c2e5e-ffffffe0006c2e9e: cec_monitor_all_cnt_dec (STB_GLOBAL)
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
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818222f0)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff818222f0-ffffffff81822322: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e9990)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817e9990-ffffffff817e99c2: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186f230)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186f230-ffffffff8186f262: cec_monitor_all_cnt_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_monitor_all_cnt_dec(struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818891b0)
Location: drivers/media/cec/cec-adap.c:2112
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_release
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff818891b0-ffffffff818891e2: cec_monitor_all_cnt_dec (STB_GLOBAL)
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

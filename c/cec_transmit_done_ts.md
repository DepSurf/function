# Function: <code>cec_transmit_done_ts</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:564
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff81806fcb-ffffffff8180706d: cec_transmit_done_ts.cold.13 (STB_LOCAL)
ffffffff818044d0-ffffffff81804712: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:577
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff81848805-ffffffff818488e6: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff81845b20-ffffffff81845d4d: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff8187a09f-ffffffff8187a145: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff81877440-ffffffff81877674: cec_transmit_done_ts (STB_GLOBAL)
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
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abee18)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffff800010abee18-ffff800010abf0cc: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0b00)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
c0ba0b00-c0ba0ddc: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0750)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
c000000000ba0750-c000000000ba0a90: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c08ae)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffe0006c08ae-ffffffe0006c0b16: cec_transmit_done_ts (STB_GLOBAL)
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
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff8182260f-ffffffff818226b5: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff8181f9b0-ffffffff8181fbe4: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff817e9caf-ffffffff817e9d55: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff817e7050-ffffffff817e7284: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff8186f54f-ffffffff8186f5f5: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff8186c8f0-ffffffff8186cb24: cec_transmit_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cec_transmit_done_ts(struct cec_adapter *adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:591
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts
```
**Symbols:**

```
ffffffff818894cf-ffffffff81889575: cec_transmit_done_ts.cold (STB_LOCAL)
ffffffff81886880-ffffffff81886ab4: cec_transmit_done_ts (STB_GLOBAL)
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

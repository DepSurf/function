# Function: <code>cec_transmit_attempt_done_ts</code>

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
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804720)
Location: drivers/media/cec/cec-adap.c:661
Inline: False
```
**Symbols:**

```
ffffffff81804720-ffffffff818047d1: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845d50)
Location: drivers/media/cec/cec-adap.c:674
Inline: False
```
**Symbols:**

```
ffffffff81845d50-ffffffff81845df2: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877680)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
ffffffff81877680-ffffffff81877722: cec_transmit_attempt_done_ts (STB_GLOBAL)
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
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abf0d0)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffff800010abf0d0-ffff800010abf23c: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0ddc)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
c0ba0ddc-c0ba0f38: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0a90)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
c000000000ba0a90-c000000000ba0bf4: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0b16)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
ffffffe0006c0b16-ffffffe0006c0bf4: cec_transmit_attempt_done_ts (STB_GLOBAL)
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
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181fbf0)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
ffffffff8181fbf0-ffffffff8181fc92: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e7290)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
ffffffff817e7290-ffffffff817e7332: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186cb30)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
```
**Symbols:**

```
ffffffff8186cb30-ffffffff8186cbd2: cec_transmit_attempt_done_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_transmit_attempt_done_ts(struct cec_adapter *adap, u8 status, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886ac0)
Location: drivers/media/cec/cec-adap.c:688
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffffffff81886ac0-ffffffff81886b62: cec_transmit_attempt_done_ts (STB_GLOBAL)
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

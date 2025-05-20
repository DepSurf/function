# Function: <code>cec_received_msg_ts</code>

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
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:977
Inline: False
```
**Symbols:**

```
ffffffff818071f5-ffffffff81807277: cec_received_msg_ts.cold.15 (STB_LOCAL)
ffffffff818053f0-ffffffff81805e39: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1022
Inline: False
```
**Symbols:**

```
ffffffff81848be2-ffffffff81848c26: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff81847530-ffffffff81847a22: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
ffffffff8187a40f-ffffffff8187a440: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff81878e80-ffffffff818792ed: cec_received_msg_ts (STB_GLOBAL)
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
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac09d8)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffff800010ac09d8-ffff800010ac0dec: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba27e4)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
c0ba27e4-c0ba2be8: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba2c10)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
c000000000ba2c10-c000000000ba3110: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c2060)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
ffffffe0006c2060-ffffffe0006c23cc: cec_received_msg_ts (STB_GLOBAL)
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
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
ffffffff8182297f-ffffffff818229b0: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff818213f0-ffffffff8182185d: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
ffffffff817ea01f-ffffffff817ea050: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff817e8a90-ffffffff817e8efd: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
```
**Symbols:**

```
ffffffff8186f8bf-ffffffff8186f8f0: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff8186e330-ffffffff8186e79d: cec_received_msg_ts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cec_received_msg_ts(struct cec_adapter *adap, struct cec_msg *msg, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1036
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffffffff8188983f-ffffffff81889870: cec_received_msg_ts.cold (STB_LOCAL)
ffffffff818882b0-ffffffff8188871d: cec_received_msg_ts (STB_GLOBAL)
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

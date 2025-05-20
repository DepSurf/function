# Function: <code>cec_queue_pin_cec_event</code>

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
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81803ef0)
Location: drivers/media/cec/cec-adap.c:158
Inline: False
```
**Symbols:**

```
ffffffff81803ef0-ffffffff81803fb5: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845530)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffff81845530-ffffffff818455f5: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81876e20)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffff81876e20-ffffffff81876ee5: cec_queue_pin_cec_event (STB_GLOBAL)
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
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abe788)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffff800010abe788-ffff800010abe87c: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba04b8)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
c0ba04b8-c0ba05a4: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000b9fe30)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
c000000000b9fe30-c000000000b9ff6c: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c032a)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffe0006c032a-ffffffe0006c03e6: cec_queue_pin_cec_event (STB_GLOBAL)
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
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f390)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffff8181f390-ffffffff8181f455: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6a30)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffff817e6a30-ffffffff817e6af5: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c2d0)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
```
**Symbols:**

```
ffffffff8186c2d0-ffffffff8186c395: cec_queue_pin_cec_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_queue_pin_cec_event(struct cec_adapter *adap, bool is_high, bool dropped_events, ktime_t ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886260)
Location: drivers/media/cec/cec-adap.c:171
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
**Symbols:**

```
ffffffff81886260-ffffffff81886325: cec_queue_pin_cec_event (STB_GLOBAL)
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

# Function: <code>pps_event</code>

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
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff817de670)
Location: drivers/pps/kapi.c:172
Inline: False
```
**Symbols:**

```
ffffffff817de670-ffffffff817de91e: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81809a90)
Location: drivers/pps/kapi.c:173
Inline: False
```
**Symbols:**

```
ffffffff81809a90-ffffffff81809d30: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff8184b700)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff8184b700-ffffffff8184b999: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff8187cf10)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff8187cf10-ffffffff8187d1a9: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff8194b3f0)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff8194b3f0-ffffffff8194b690: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81950ed0)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81950ed0-ffffffff81951170: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81934d50)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81934d50-ffffffff81934ff0: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff819d8170)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff819d8170-ffffffff819d8410: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81b3b530)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81b3b530-ffffffff81b3b7cd: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81cd1360)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81cd1360-ffffffff81cd160b: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81d38da0)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81d38da0-ffffffff81d3904b: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81def040)
Location: drivers/pps/kapi.c:159
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81def040-ffffffff81def2eb: pps_event (STB_GLOBAL)
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
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffff800010ac67c0)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffff800010ac67c0-ffff800010ac6aa4: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (c0ba63f4)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
c0ba63f4-c0ba661c: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (c000000000ba7bb0)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
c000000000ba7bb0-c000000000ba7f38: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffe0006c51ec)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffe0006c51ec-ffffffe0006c5442: pps_event (STB_GLOBAL)
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
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff81825480)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff81825480-ffffffff81825719: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff817ecb10)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff817ecb10-ffffffff817ecda9: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff818723c0)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff818723c0-ffffffff81872659: pps_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pps_event(struct pps_device *pps, struct pps_event_time *ts, int event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/kapi.c (ffffffff8188dd70)
Location: drivers/pps/kapi.c:159
Inline: False
```
**Symbols:**

```
ffffffff8188dd70-ffffffff8188e009: pps_event (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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

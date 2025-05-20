# Function: <code>wakeup_source_report_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155ba80)
Location: drivers/base/power/wakeup.c:552
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:__pm_stay_awake
  - drivers/base/power/wakeup.c:__pm_wakeup_event
```
**Symbols:**

```
ffffffff8155ba80-ffffffff8155bb8d: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adc90)
Location: drivers/base/power/wakeup.c:550
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/base/power/wakeup.c:__pm_stay_awake
```
**Symbols:**

```
ffffffff815adc90-ffffffff815add96: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dca60)
Location: drivers/base/power/wakeup.c:550
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/base/power/wakeup.c:__pm_stay_awake
```
**Symbols:**

```
ffffffff815dca60-ffffffff815dcb66: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1bf0)
Location: drivers/base/power/wakeup.c:547
Inline: True
```
**Symbols:**

```
ffffffff815f1bf0-ffffffff815f1d0a: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816591a0)
Location: drivers/base/power/wakeup.c:548
Inline: True
```
**Symbols:**

```
ffffffff816591a0-ffffffff816592bf: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694e90)
Location: drivers/base/power/wakeup.c:547
Inline: True
```
**Symbols:**

```
ffffffff81694e90-ffffffff81694fad: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5530)
Location: drivers/base/power/wakeup.c:553
Inline: True
```
**Symbols:**

```
ffffffff816b5530-ffffffff816b564d: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef0d0)
Location: drivers/base/power/wakeup.c:537
Inline: True
```
**Symbols:**

```
ffffffff816ef0d0-ffffffff816ef1ef: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713230)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffffffff81713230-ffffffff8171334f: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf15f)
Location: drivers/base/power/wakeup.c:616
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e375f)
Location: drivers/base/power/wakeup.c:616
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c791f)
Location: drivers/base/power/wakeup.c:617
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:618
Inline: False
```
**Symbols:**

```
ffffffff81851c20-ffffffff81851d35: wakeup_source_report_event (STB_LOCAL)
ffffffff81d03ece-ffffffff81d03ef7: wakeup_source_report_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:618
Inline: False
```
**Symbols:**

```
ffffffff81997c90-ffffffff81997d11: wakeup_source_report_event (STB_LOCAL)
ffffffff81ecc802-ffffffff81ecc817: wakeup_source_report_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:588
Inline: False
```
**Symbols:**

```
ffffffff81b08d70-ffffffff81b08df1: wakeup_source_report_event (STB_LOCAL)
ffffffff82098994-ffffffff820989a9: wakeup_source_report_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:583
Inline: False
```
**Symbols:**

```
ffffffff81b56d90-ffffffff81b56e11: wakeup_source_report_event (STB_LOCAL)
ffffffff82119960-ffffffff82119975: wakeup_source_report_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:583
Inline: False
```
**Symbols:**

```
ffffffff81baf380-ffffffff81baf401: wakeup_source_report_event (STB_LOCAL)
ffffffff821f7922-ffffffff821f7937: wakeup_source_report_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010903c50)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffff800010903c50-ffff800010903e04: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09edd48)
Location: drivers/base/power/wakeup.c:557
Inline: False
```
**Symbols:**

```
c09edd48-c09eded0: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a29b0)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
c0000000009a29b0-c0000000009a2be4: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d95b0)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffffffff816d95b0-ffffffff816d96ba: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3bf0)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffffffff816b3bf0-ffffffff816b3d0f: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706ef0)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffffffff81706ef0-ffffffff8170700f: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_report_event(struct wakeup_source *ws, bool hard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721920)
Location: drivers/base/power/wakeup.c:557
Inline: True
```
**Symbols:**

```
ffffffff81721920-ffffffff81721a58: wakeup_source_report_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool hard</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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

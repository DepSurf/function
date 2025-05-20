# Function: <code>clockevents_program_min_delta</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff810fb740)
Location: kernel/time/clockevents.c:241
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff810fb740-ffffffff810fb82c: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81102a60)
Location: kernel/time/clockevents.c:241
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81102a60-ffffffff81102b51: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a150)
Location: kernel/time/clockevents.c:241
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff8110a150-ffffffff8110a241: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c0b0)
Location: kernel/time/clockevents.c:241
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff8110c0b0-ffffffff8110c1a1: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81117300)
Location: kernel/time/clockevents.c:241
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81117300-ffffffff811173f7: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811246bc)
Location: kernel/time/clockevents.c:241
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_program_event
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff811240c0-ffffffff8112412e: clockevents_program_min_delta.part.10 (STB_LOCAL)
ffffffff81124ac9-ffffffff81124b4c: clockevents_program_min_delta.part.10.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112fdbc)
Location: kernel/time/clockevents.c:233
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_program_event
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff8112f7c0-ffffffff8112f82e: clockevents_program_min_delta.part.11 (STB_LOCAL)
ffffffff811301c9-ffffffff8113024c: clockevents_program_min_delta.part.11.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81139ff0-ffffffff8113a05e: clockevents_program_min_delta (STB_LOCAL)
ffffffff8113acc9-ffffffff8113ad4e: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81145c60-ffffffff81145cc4: clockevents_program_min_delta (STB_LOCAL)
ffffffff8114691f-ffffffff811469aa: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81155a80-ffffffff81155ae4: clockevents_program_min_delta (STB_LOCAL)
ffffffff811567df-ffffffff8115686a: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81151c20-ffffffff81151c84: clockevents_program_min_delta (STB_LOCAL)
ffffffff81be3c3f-ffffffff81be3cca: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff811530b0-ffffffff81153114: clockevents_program_min_delta (STB_LOCAL)
ffffffff81bd5b58-ffffffff81bd5be3: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81177670-ffffffff811776ed: clockevents_program_min_delta (STB_LOCAL)
ffffffff81cb1f8a-ffffffff81cb2031: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff811ac700-ffffffff811ac789: clockevents_program_min_delta (STB_LOCAL)
ffffffff81e634ee-ffffffff81e63595: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff811ecaa0-ffffffff811ecbb3: clockevents_program_min_delta (STB_LOCAL)
ffffffff8205bcec-ffffffff8205bd08: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff812011d0-ffffffff812012e3: clockevents_program_min_delta (STB_LOCAL)
ffffffff820da4ec-ffffffff820da508: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81217670-ffffffff81217783: clockevents_program_min_delta (STB_LOCAL)
ffffffff821b5e66-ffffffff821b5e82: clockevents_program_min_delta.cold (STB_LOCAL)
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
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0350)
Location: kernel/time/clockevents.c:272
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffff8000101b0350-ffff8000101b03f0: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fb05c)
Location: kernel/time/clockevents.c:272
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
c03fb05c-c03fb110: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000214d70)
Location: kernel/time/clockevents.c:272
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
c000000000214d70-c000000000214e60: clockevents_program_min_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139388)
Location: kernel/time/clockevents.c:272
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffe000139388-ffffffe000139408: clockevents_program_min_delta (STB_LOCAL)
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
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff8113e410-ffffffff8113e474: clockevents_program_min_delta (STB_LOCAL)
ffffffff8113f0cf-ffffffff8113f15a: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81130f30-ffffffff81130f94: clockevents_program_min_delta (STB_LOCAL)
ffffffff81131bcf-ffffffff81131c5a: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff8113c130-ffffffff8113c194: clockevents_program_min_delta (STB_LOCAL)
ffffffff8113cdef-ffffffff8113ce7a: clockevents_program_min_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int clockevents_program_min_delta(struct clock_event_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:233
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevents_program_event
```
**Symbols:**

```
ffffffff81148c10-ffffffff81148c74: clockevents_program_min_delta (STB_LOCAL)
ffffffff811498df-ffffffff8114996a: clockevents_program_min_delta.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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

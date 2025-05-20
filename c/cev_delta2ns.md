# Function: <code>cev_delta2ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff810fb670)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff810fb670-ffffffff810fb71b: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81102990)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81102990-ffffffff81102a3b: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a080)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff8110a080-ffffffff8110a12b: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c010)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff8110c010-ffffffff8110c08e: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81117260)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81117260-ffffffff811172de: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81123e00)
Location: kernel/time/clockevents.c:36
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81123e00-ffffffff81123e7e: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112f4d0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff8112f4d0-ffffffff8112f54e: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81139f40-ffffffff81139fce: cev_delta2ns (STB_LOCAL)
ffffffff8113ac9f-ffffffff8113acc9: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81145bc0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81145bc0-ffffffff81145c3d: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81156185)
Location: kernel/time/clockevents.c:32
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81155940-ffffffff811559c4: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81152325)
Location: kernel/time/clockevents.c:32
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81151ae0-ffffffff81151b64: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81153415)
Location: kernel/time/clockevents.c:32
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81152f80-ffffffff81153000: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81177580-ffffffff8117764d: cev_delta2ns (STB_LOCAL)
ffffffff81cb1f06-ffffffff81cb1f8a: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff811ac610-ffffffff811ac6d5: cev_delta2ns (STB_LOCAL)
ffffffff81e63463-ffffffff81e634ee: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff811ec990-ffffffff811eca55: cev_delta2ns (STB_LOCAL)
ffffffff8205bc61-ffffffff8205bcec: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff812010c0-ffffffff81201185: cev_delta2ns (STB_LOCAL)
ffffffff820da463-ffffffff820da4ec: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81217560-ffffffff81217625: cev_delta2ns (STB_LOCAL)
ffffffff821b5ddd-ffffffff821b5e66: cev_delta2ns.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0508)
Location: kernel/time/clockevents.c:32
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffff8000101b0508-ffff8000101b05d8: cev_delta2ns.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fae98)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
c03fae98-c03fb03c: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (c0000000002153b0)
Location: kernel/time/clockevents.c:32
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
c0000000002153b0-c00000000021545c: cev_delta2ns.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffe0001394e2)
Location: kernel/time/clockevents.c:32
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffe0001394e2-ffffffe000139578: cev_delta2ns.isra.0 (STB_LOCAL)
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
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113e370)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff8113e370-ffffffff8113e3ed: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81130e90)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81130e90-ffffffff81130f0d: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113c090)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff8113c090-ffffffff8113c10d: cev_delta2ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 cev_delta2ns(long unsigned int latch, struct clock_event_device *evt, bool ismax);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81148b70)
Location: kernel/time/clockevents.c:32
Inline: False
Direct callers:
  - kernel/time/clockevents.c:clockevent_delta2ns
```
**Symbols:**

```
ffffffff81148b70-ffffffff81148bed: cev_delta2ns (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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

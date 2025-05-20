# Function: <code>sh_cmt_start</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
int sh_cmt_start(struct sh_cmt_channel *ch, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (ffff800010b64cb8)
Location: drivers/clocksource/sh_cmt.c:556
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_set_state
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_set_state
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_resume
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_enable
```
**Symbols:**

```
ffff800010b64cb8-ffff800010b64f24: sh_cmt_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sh_cmt_start(struct sh_cmt_channel *ch, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (c0c44864)
Location: drivers/clocksource/sh_cmt.c:556
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_set_state
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_set_state
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_resume
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_enable
```
**Symbols:**

```
c0c44864-c0c44a68: sh_cmt_start (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

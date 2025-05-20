# Function: <code>sh_cmt_get_counter</code>

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
u32 sh_cmt_get_counter(struct sh_cmt_channel *ch, u32 *has_wrapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (ffff800010b63d98)
Location: drivers/clocksource/sh_cmt.c:275
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_program_verify
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_program_verify
```
**Symbols:**

```
ffff800010b63d98-ffff800010b63eb0: sh_cmt_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 sh_cmt_get_counter(struct sh_cmt_channel *ch, u32 *has_wrapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (c0c441e0)
Location: drivers/clocksource/sh_cmt.c:275
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_program_verify
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_program_verify
```
**Symbols:**

```
c0c441e0-c0c442ec: sh_cmt_get_counter (STB_LOCAL)
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

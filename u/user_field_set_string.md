# Function: <code>user_field_set_string</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int user_field_set_string(struct ftrace_event_field *field, char *buf, int len, bool colon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_user.c (ffffffff812c3570)
Location: kernel/trace/trace_events_user.c:1311
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_field_match
  - kernel/trace/trace_events_user.c:user_field_match
```
**Symbols:**

```
ffffffff812c3570-ffffffff812c36b7: user_field_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int user_field_set_string(struct ftrace_event_field *field, char *buf, int len, bool colon);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_user.c (ffffffff812dfdd0)
Location: kernel/trace/trace_events_user.c:1348
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_field_match
  - kernel/trace/trace_events_user.c:user_field_match
```
**Symbols:**

```
ffffffff812dfdd0-ffffffff812dff17: user_field_set_string (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

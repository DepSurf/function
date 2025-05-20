# Function: <code>add_to_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171c34)
Location: kernel/trace/trace_events_hist.c:855
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117d3a4)
Location: kernel/trace/trace_events_hist.c:855
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117ff37)
Location: kernel/trace/trace_events_hist.c:856
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118d7ce)
Location: kernel/trace/trace_events_hist.c:899
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c6cf)
Location: kernel/trace/trace_events_hist.c:4594
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aaa8f)
Location: kernel/trace/trace_events_hist.c:4679
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8af4)
Location: kernel/trace/trace_events_hist.c:5195
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c40d4)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_to_key(char *compound_key, void *key, struct hist_field *key_field, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0830)
Location: kernel/trace/trace_events_hist.c:4413
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811e0830-ffffffff811e08ba: add_to_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_to_key(char *compound_key, void *key, struct hist_field *key_field, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811de190)
Location: kernel/trace/trace_events_hist.c:4454
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811de190-ffffffff811de21a: add_to_key (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811dfb3b)
Location: kernel/trace/trace_events_hist.c:4523
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8120ff9b)
Location: kernel/trace/trace_events_hist.c:4621
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124cc32)
Location: kernel/trace/trace_events_hist.c:5000
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_to_key(char *compound_key, void *key, struct hist_field *key_field, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129add0)
Location: kernel/trace/trace_events_hist.c:5131
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8129add0-ffffffff8129ae7e: add_to_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_to_key(char *compound_key, void *key, struct hist_field *key_field, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812b8540)
Location: kernel/trace/trace_events_hist.c:5220
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812b8540-ffffffff812b85ee: add_to_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_to_key(char *compound_key, void *key, struct hist_field *key_field, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d4b90)
Location: kernel/trace/trace_events_hist.c:5212
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812d4b90-ffffffff812d4c3e: add_to_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010243ce8)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6d3c)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc6f4)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811af4d4)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ba4c4)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8564)
Location: kernel/trace/trace_events_hist.c:5305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

# Function: <code>calc_tpm2_event_size</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int calc_tpm2_event_size(struct tcg_pcr_event2 *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2_eventlog.c (ffffffff815bbc90)
Location: drivers/char/tpm/tpm2_eventlog.c:39
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_next
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_next
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_start
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff815bbc90-ffffffff815bbd1f: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int calc_tpm2_event_size(struct tcg_pcr_event2 *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2_eventlog.c (ffffffff816221e0)
Location: drivers/char/tpm/tpm2_eventlog.c:39
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_next
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_next
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_start
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff816221e0-ffffffff8162226f: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int calc_tpm2_event_size(struct tcg_pcr_event2 *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8165bfb0)
Location: drivers/char/tpm/eventlog/tpm2.c:40
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff8165bfb0-ffffffff8165c03f: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int calc_tpm2_event_size(struct tcg_pcr_event2 *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8167b000)
Location: drivers/char/tpm/eventlog/tpm2.c:40
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff8167b000-ffffffff8167b08f: calc_tpm2_event_size (STB_LOCAL)
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816b1b8f)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816d486f)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81788a74)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8179fa04)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff817826b4)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81809074)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t calc_tpm2_event_size(struct tcg_pcr_event2_head *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81948e50)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff81948e50-ffffffff81948f8e: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t calc_tpm2_event_size(struct tcg_pcr_event2_head *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81aac390)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff81aac390-ffffffff81aac4c4: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t calc_tpm2_event_size(struct tcg_pcr_event2_head *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81af7bf0)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff81af7bf0-ffffffff81af7d1f: calc_tpm2_event_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t calc_tpm2_event_size(struct tcg_pcr_event2_head *event, struct tcg_pcr_event *event_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81b4b210)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
**Symbols:**

```
ffffffff81b4b210-ffffffff81b4b33f: calc_tpm2_event_size (STB_LOCAL)
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
In drivers/char/tpm/eventlog/tpm2.c (ffff8000108bf5a4)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (c09b89b4)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (c000000000961e18)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffe000571b04)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8169a2bf)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81677caf)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816c852f)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816e2a0f)
Location: drivers/char/tpm/eventlog/tpm2.c:36
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

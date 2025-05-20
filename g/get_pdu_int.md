# Function: <code>get_pdu_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u64 get_pdu_int(const struct trace_entry *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115acf0)
Location: kernel/trace/blktrace.c:1119
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
**Symbols:**

```
ffffffff8115acf0-ffffffff8115acfd: get_pdu_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81165c5c)
Location: kernel/trace/blktrace.c:1121
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811710bc)
Location: kernel/trace/blktrace.c:1121
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff8117400c)
Location: kernel/trace/blktrace.c:1099
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff81181271)
Location: kernel/trace/blktrace.c:1232
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff81190401)
Location: kernel/trace/blktrace.c:1232
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff8119e1f1)
Location: kernel/trace/blktrace.c:1220
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811abee1)
Location: kernel/trace/blktrace.c:1215
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811b7741)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811cfca1)
Location: kernel/trace/blktrace.c:1287
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811cd141)
Location: kernel/trace/blktrace.c:1229
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811ce445)
Location: kernel/trace/blktrace.c:1228
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811fae91)
Location: kernel/trace/blktrace.c:1238
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff81235051)
Location: kernel/trace/blktrace.c:1238
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812819a1)
Location: kernel/trace/blktrace.c:1239
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8129e651)
Location: kernel/trace/blktrace.c:1235
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812b9d31)
Location: kernel/trace/blktrace.c:1235
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
__u64 get_pdu_int(const struct trace_entry *ent, bool has_cg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010236240)
Location: kernel/trace/blktrace.c:1260
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
**Symbols:**

```
ffff800010236240-ffff80001023625c: get_pdu_int (STB_LOCAL)
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
In kernel/trace/blktrace.c (c04710bc)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (c0000000002c0b48)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__u64 get_pdu_int(const struct trace_entry *ent, bool has_cg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018ea8a)
Location: kernel/trace/blktrace.c:1260
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
**Symbols:**

```
ffffffe00018ea8a-ffffffe00018eaf8: get_pdu_int (STB_LOCAL)
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
In kernel/trace/blktrace.c (ffffffff811afd61)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811a2bb1)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811adb31)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
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
In kernel/trace/blktrace.c (ffffffff811bba01)
Location: kernel/trace/blktrace.c:1260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_split
  - kernel/trace/blktrace.c:blk_log_unplug
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>

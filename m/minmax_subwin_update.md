# Function: <code>minmax_subwin_update</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff818c5d30)
Location: lib/win_minmax.c:28
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff818c5d30-ffffffff818c5da5: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff818fb250)
Location: lib/win_minmax.c:28
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff818fb250-ffffffff818fb2c5: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81981eb0)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81981eb0-ffffffff81981f25: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff819de400)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff819de400-ffffffff819de470: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81a16a50)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81a16a50-ffffffff81a16ac0: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81a865e0)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81a865e0-ffffffff81a86650: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81abd860)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81abd860-ffffffff81abd8d0: minmax_subwin_update (STB_LOCAL)
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
In lib/win_minmax.c (ffffffff815f99db)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff8161e09b)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff816019f3)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff8166f983)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff81789dcf)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff820471df)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff820c586f)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
In lib/win_minmax.c (ffffffff821a01ef)
Location: lib/win_minmax.c:29
Inline: True
Inline callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
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
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffff800010d98ac8)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffff800010d98ac8-ffff800010d98b58: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (c0e954d0)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
  - lib/win_minmax.c:minmax_running_max
```
**Symbols:**

```
c0e954d0-c0e9559c: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (c000000000ede220)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
c000000000ede220-c000000000ede2d8: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffe0008c187a)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffe0008c187a-ffffffe0008c190e: minmax_subwin_update (STB_LOCAL)
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
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81a5c6b0)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81a5c6b0-ffffffff81a5c720: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81a19790)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81a19790-ffffffff81a19800: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81ac8aa0)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81ac8aa0-ffffffff81ac8b10: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 minmax_subwin_update(struct minmax *m, u32 win, const struct minmax_sample *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/win_minmax.c (ffffffff81ad4f80)
Location: lib/win_minmax.c:29
Inline: False
Direct callers:
  - lib/win_minmax.c:minmax_running_min
```
**Symbols:**

```
ffffffff81ad4f80-ffffffff81ad4ff0: minmax_subwin_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

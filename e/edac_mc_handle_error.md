# Function: <code>edac_mc_handle_error</code>

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
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175c6e0)
Location: drivers/edac/edac_mc.c:1086
Inline: False
```
**Symbols:**

```
ffffffff8175c6e0-ffffffff8175ce71: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817ce930)
Location: drivers/edac/edac_mc.c:1091
Inline: False
```
**Symbols:**

```
ffffffff817ce930-ffffffff817ceee9: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1093
Inline: False
```
**Symbols:**

```
ffffffff8181868c-ffffffff818186ba: edac_mc_handle_error.cold.15 (STB_LOCAL)
ffffffff81817510-ffffffff81817a6d: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81843f25-ffffffff81843f53: edac_mc_handle_error.cold.16 (STB_LOCAL)
ffffffff81842db0-ffffffff8184330d: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1082
Inline: False
```
**Symbols:**

```
ffffffff81886cdd-ffffffff81886d08: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff81885bc0-ffffffff81886146: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffff818b8c9d-ffffffff818b8cc8: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff818b7b60-ffffffff818b810b: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1012
Inline: False
```
**Symbols:**

```
ffffffff819894b8-ffffffff819894f6: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff819888e0-ffffffff81988d51: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1016
Inline: False
```
**Symbols:**

```
ffffffff81c288ed-ffffffff81c2893b: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff8198c660-ffffffff8198cbb0: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1016
Inline: False
```
**Symbols:**

```
ffffffff81c1aad6-ffffffff81c1ab24: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff81970d60-ffffffff819712ae: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81d2a9d2-ffffffff81d2a9ea: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff81a19680-ffffffff81a19d86: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81b82570)
Location: drivers/edac/edac_mc.c:944
Inline: False
```
**Symbols:**

```
ffffffff81b82570-ffffffff81b82b9a: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d20f30)
Location: drivers/edac/edac_mc.c:943
Inline: False
```
**Symbols:**

```
ffffffff81d20f30-ffffffff81d214df: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d8a130)
Location: drivers/edac/edac_mc.c:943
Inline: False
```
**Symbols:**

```
ffffffff81d8a130-ffffffff81d8a6df: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e41880)
Location: drivers/edac/edac_mc.c:944
Inline: False
```
**Symbols:**

```
ffffffff81e41880-ffffffff81e41e2f: edac_mc_handle_error (STB_GLOBAL)
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
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b0fff8)
Location: drivers/edac/edac_mc.c:1075
Inline: False
Direct callers:
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
```
**Symbols:**

```
ffff800010b0fff8-ffff800010b10548: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0bee0b0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
Direct callers:
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
```
**Symbols:**

```
c0bee0b0-c0bee6c0: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c035b0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
c000000000c035b0-c000000000c03c50: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fd08a)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffe0006fd08a-ffffffe0006fd5da: edac_mc_handle_error (STB_GLOBAL)
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
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffff8185eb1d-ffffffff8185eb48: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff8185d9e0-ffffffff8185df8b: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffff818260ed-ffffffff81826118: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff81824fb0-ffffffff8182555b: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffff818ae14d-ffffffff818ae178: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff818ad010-ffffffff818ad5bb: edac_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char *msg, const char *other_detail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1075
Inline: False
```
**Symbols:**

```
ffffffff818ca3dd-ffffffff818ca408: edac_mc_handle_error.cold (STB_LOCAL)
ffffffff818c9280-ffffffff818c9844: edac_mc_handle_error (STB_GLOBAL)
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

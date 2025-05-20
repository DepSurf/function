# Function: <code>edac_raw_mc_handle_error</code>

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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175c1b0)
Location: drivers/edac/edac_mc.c:1057
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
ffffffff8175c1b0-ffffffff8175c6d5: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817ce3f0)
Location: drivers/edac/edac_mc.c:1062
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff817ce3f0-ffffffff817ce927: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1064
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81818516-ffffffff8181868c: edac_raw_mc_handle_error.cold.14 (STB_LOCAL)
ffffffff81817120-ffffffff81817506: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1057
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81843daf-ffffffff81843f25: edac_raw_mc_handle_error.cold.15 (STB_LOCAL)
ffffffff818429c0-ffffffff81842da6: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1053
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81886b5d-ffffffff81886cdd: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff818857c0-ffffffff81885bb8: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff818b8b1d-ffffffff818b8c9d: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff818b7760-ffffffff818b7b58: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81988720)
Location: drivers/edac/edac_mc.c:986
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81988720-ffffffff819888d9: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198c500)
Location: drivers/edac/edac_mc.c:990
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff8198c500-ffffffff8198c658: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:990
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81c1a9f9-ffffffff81c1aad6: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff81970b10-ffffffff81970d54: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:993
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81d2a8f5-ffffffff81d2a9d2: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff81a19430-ffffffff81a19671: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:918
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81ef6a48-ffffffff81ef6ba3: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff81b821d0-ffffffff81b82562: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d20a40)
Location: drivers/edac/edac_mc.c:917
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81d20a40-ffffffff81d20f1b: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d89c50)
Location: drivers/edac/edac_mc.c:917
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81d89c50-ffffffff81d8a118: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e413a0)
Location: drivers/edac/edac_mc.c:918
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81e413a0-ffffffff81e41868: edac_raw_mc_handle_error (STB_GLOBAL)
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b0fbe0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffff800010b0fbe0-ffff800010b0fff4: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0bedbb4)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
c0bedbb4-c0bee0b0: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c02fb0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
c000000000c02fb0-c000000000c035a8: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fccf6)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
ffffffe0006fccf6-ffffffe0006fd08a: edac_raw_mc_handle_error (STB_GLOBAL)
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
ffffffff8185e99d-ffffffff8185eb1d: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff8185d5e0-ffffffff8185d9d8: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
**Symbols:**

```
ffffffff81825f6d-ffffffff818260ed: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff81824bb0-ffffffff81824fa8: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff818adfcd-ffffffff818ae14d: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff818acc10-ffffffff818ad008: edac_raw_mc_handle_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info *mci, struct edac_raw_error_desc *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:1046
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff818ca25d-ffffffff818ca3dd: edac_raw_mc_handle_error.cold (STB_LOCAL)
ffffffff818c8e60-ffffffff818c9271: edac_raw_mc_handle_error (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const enum hw_event_mc_err_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_ctl_info *mci</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, mci, e</code> ➡️ <code>e</code>
</li>
</ul>
</details>
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

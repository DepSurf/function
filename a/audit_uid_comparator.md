# Function: <code>audit_uid_comparator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81125570)
Location: kernel/auditfilter.c:1190
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter_user
  - kernel/auditfilter.c:audit_filter_user
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
```
**Symbols:**

```
ffffffff81125570-ffffffff811255bf: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d530)
Location: kernel/auditfilter.c:1190
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff8112d530-ffffffff8112d57f: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137260)
Location: kernel/auditfilter.c:1191
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81137260-ffffffff811372af: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811387c0)
Location: kernel/auditfilter.c:1189
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff811387c0-ffffffff8113880f: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811454c0)
Location: kernel/auditfilter.c:1214
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff811454c0-ffffffff8114550f: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153e60)
Location: kernel/auditfilter.c:1211
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81153e60-ffffffff81153eaf: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81160c00)
Location: kernel/auditfilter.c:1209
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81160c00-ffffffff81160c57: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116d280)
Location: kernel/auditfilter.c:1214
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116d280-ffffffff8116d2e8: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81179120)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81179120-ffffffff81179188: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118c160)
Location: kernel/auditfilter.c:1220
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff8118c160-ffffffff8118c1c8: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81189380)
Location: kernel/auditfilter.c:1220
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff81189380-ffffffff811893e8: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a1f0)
Location: kernel/auditfilter.c:1220
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff8118a1f0-ffffffff8118a255: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b2cb0)
Location: kernel/auditfilter.c:1220
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff811b2cb0-ffffffff811b2d15: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e5070)
Location: kernel/auditfilter.c:1228
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff811e5070-ffffffff811e511b: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122b0b0)
Location: kernel/auditfilter.c:1228
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff8122b0b0-ffffffff8122b15b: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff812416a0)
Location: kernel/auditfilter.c:1228
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff812416a0-ffffffff81241740: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125b4d0)
Location: kernel/auditfilter.c:1229
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
ffffffff8125b4d0-ffffffff8125b570: audit_uid_comparator (STB_GLOBAL)
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
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ee300)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffff8000101ee300-ffff8000101ee3dc: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042e3c8)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_uid
  - kernel/auditsc.c:audit_compare_uid
```
**Symbols:**

```
c042e3c8-c042e46c: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c000000000260ea0)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
c000000000260ea0-c000000000260fb8: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe0001624ae)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffe0001624ae-ffffffe00016257e: audit_uid_comparator (STB_GLOBAL)
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
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81171740)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81171740-ffffffff811717a8: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811648e0)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811648e0-ffffffff81164948: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116f510)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116f510-ffffffff8116f578: audit_uid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_uid_comparator(kuid_t left, u32 op, kuid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117cd00)
Location: kernel/auditfilter.c:1221
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117cd00-ffffffff8117cd68: audit_uid_comparator (STB_GLOBAL)
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

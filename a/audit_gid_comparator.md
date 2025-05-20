# Function: <code>audit_gid_comparator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811255c0)
Location: kernel/auditfilter.c:1213
Inline: True
Direct callers:
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
```
**Symbols:**

```
ffffffff811255c0-ffffffff8112560f: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d580)
Location: kernel/auditfilter.c:1213
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff8112d580-ffffffff8112d5cf: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811372b0)
Location: kernel/auditfilter.c:1214
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff811372b0-ffffffff811372ff: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81138810)
Location: kernel/auditfilter.c:1212
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81138810-ffffffff8113885f: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81145510)
Location: kernel/auditfilter.c:1237
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81145510-ffffffff8114555f: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153eb0)
Location: kernel/auditfilter.c:1234
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81153eb0-ffffffff81153eff: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81160c60)
Location: kernel/auditfilter.c:1232
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81160c60-ffffffff81160cb7: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116d2f0)
Location: kernel/auditfilter.c:1236
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116d2f0-ffffffff8116d358: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81179190)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81179190-ffffffff811791f8: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118c1d0)
Location: kernel/auditfilter.c:1242
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff8118c1d0-ffffffff8118c238: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811893f0)
Location: kernel/auditfilter.c:1242
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff811893f0-ffffffff81189458: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a260)
Location: kernel/auditfilter.c:1242
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff8118a260-ffffffff8118a2c5: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b2d20)
Location: kernel/auditfilter.c:1242
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff811b2d20-ffffffff811b2d85: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e5120)
Location: kernel/auditfilter.c:1250
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff811e5120-ffffffff811e51cb: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122b170)
Location: kernel/auditfilter.c:1250
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff8122b170-ffffffff8122b21b: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81241750)
Location: kernel/auditfilter.c:1250
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff81241750-ffffffff812417f0: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125b580)
Location: kernel/auditfilter.c:1251
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
ffffffff8125b580-ffffffff8125b620: audit_gid_comparator (STB_GLOBAL)
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
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ee3e0)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
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
ffff8000101ee3e0-ffff8000101ee4bc: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042e46c)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_compare_gid
  - kernel/auditsc.c:audit_compare_gid
```
**Symbols:**

```
c042e46c-c042e510: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c000000000260fc0)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
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
c000000000260fc0-c0000000002610d8: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe00016257e)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
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
ffffffe00016257e-ffffffe00016264e: audit_gid_comparator (STB_GLOBAL)
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
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811717b0)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811717b0-ffffffff81171818: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81164950)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81164950-ffffffff811649b8: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116f580)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116f580-ffffffff8116f5e8: audit_gid_comparator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_gid_comparator(kgid_t left, u32 op, kgid_t right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117cd70)
Location: kernel/auditfilter.c:1243
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117cd70-ffffffff8117cdd8: audit_gid_comparator (STB_GLOBAL)
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

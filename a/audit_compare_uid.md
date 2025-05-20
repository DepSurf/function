# Function: <code>audit_compare_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81126bd0)
Location: kernel/auditsc.c:310
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
```
**Symbols:**

```
ffffffff81126bd0-ffffffff81126c47: audit_compare_uid.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8112ece0)
Location: kernel/auditsc.c:311
Inline: True
```
**Symbols:**

```
ffffffff8112ece0-ffffffff8112ed56: audit_compare_uid.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81138a20)
Location: kernel/auditsc.c:311
Inline: True
```
**Symbols:**

```
ffffffff81138a20-ffffffff81138a96: audit_compare_uid.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a050)
Location: kernel/auditsc.c:312
Inline: True
```
**Symbols:**

```
ffffffff8113a050-ffffffff8113a0c6: audit_compare_uid.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81146d20)
Location: kernel/auditsc.c:312
Inline: True
```
**Symbols:**

```
ffffffff81146d20-ffffffff81146d96: audit_compare_uid.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811556d0)
Location: kernel/auditsc.c:312
Inline: True
```
**Symbols:**

```
ffffffff811556d0-ffffffff81155746: audit_compare_uid.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81162a80)
Location: kernel/auditsc.c:306
Inline: True
```
**Symbols:**

```
ffffffff81162a80-ffffffff81162af6: audit_compare_uid.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8116e900)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116e900-ffffffff8116e976: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8117a780)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117a780-ffffffff8117a7f6: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c6b0)
Location: kernel/auditsc.c:317
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8118c6b0-ffffffff8118c727: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81189880)
Location: kernel/auditsc.c:333
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81189880-ffffffff811898f7: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118a880)
Location: kernel/auditsc.c:333
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8118a880-ffffffff8118a8f7: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b3460)
Location: kernel/auditsc.c:339
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811b3460-ffffffff811b34d7: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e58b0)
Location: kernel/auditsc.c:329
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811e58b0-ffffffff811e593f: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122b950)
Location: kernel/auditsc.c:329
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8122b950-ffffffff8122b9df: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81241f30)
Location: kernel/auditsc.c:330
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81241f30-ffffffff81241fbf: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125bd40)
Location: kernel/auditsc.c:332
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8125bd40-ffffffff8125bdcf: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffff8000101ef910)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffff8000101ef910-ffff8000101ef9ac: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_compare_uid(kuid_t uid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042ea84)
Location: kernel/auditsc.c:306
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
c042ea84-c042eb00: audit_compare_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (c000000000262560)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
c000000000262560-c000000000262654: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffe000163604)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffe000163604-ffffffe000163686: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81172da0)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81172da0-ffffffff81172e16: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81165f40)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81165f40-ffffffff81165fb6: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81170b70)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81170b70-ffffffff81170be6: audit_compare_uid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8117e380)
Location: kernel/auditsc.c:306
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117e380-ffffffff8117e3f6: audit_compare_uid.isra.0 (STB_LOCAL)
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
</ul>

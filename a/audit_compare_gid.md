# Function: <code>audit_compare_gid</code>

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
In kernel/auditsc.c (ffffffff81126c50)
Location: kernel/auditsc.c:334
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
```
**Symbols:**

```
ffffffff81126c50-ffffffff81126cc7: audit_compare_gid.isra.4 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8112ed60)
Location: kernel/auditsc.c:335
Inline: True
```
**Symbols:**

```
ffffffff8112ed60-ffffffff8112edd6: audit_compare_gid.isra.4 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81138aa0)
Location: kernel/auditsc.c:335
Inline: True
```
**Symbols:**

```
ffffffff81138aa0-ffffffff81138b16: audit_compare_gid.isra.6 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8113a0d0)
Location: kernel/auditsc.c:336
Inline: True
```
**Symbols:**

```
ffffffff8113a0d0-ffffffff8113a146: audit_compare_gid.isra.10 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81146da0)
Location: kernel/auditsc.c:336
Inline: True
```
**Symbols:**

```
ffffffff81146da0-ffffffff81146e16: audit_compare_gid.isra.10 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81155750)
Location: kernel/auditsc.c:336
Inline: True
```
**Symbols:**

```
ffffffff81155750-ffffffff811557c6: audit_compare_gid.isra.13 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81162b00)
Location: kernel/auditsc.c:330
Inline: True
```
**Symbols:**

```
ffffffff81162b00-ffffffff81162b76: audit_compare_gid.isra.8 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8116e980)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8116e980-ffffffff8116e9f6: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117a800)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117a800-ffffffff8117a876: audit_compare_gid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c730)
Location: kernel/auditsc.c:341
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8118c730-ffffffff8118c7a7: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81189900)
Location: kernel/auditsc.c:357
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81189900-ffffffff81189977: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118a900)
Location: kernel/auditsc.c:357
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8118a900-ffffffff8118a977: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b34e0)
Location: kernel/auditsc.c:363
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811b34e0-ffffffff811b3557: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e5940)
Location: kernel/auditsc.c:353
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff811e5940-ffffffff811e59cf: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122b9f0)
Location: kernel/auditsc.c:353
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8122b9f0-ffffffff8122ba7f: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81241fd0)
Location: kernel/auditsc.c:354
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81241fd0-ffffffff8124205f: audit_compare_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125bde0)
Location: kernel/auditsc.c:356
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8125bde0-ffffffff8125be6f: audit_compare_gid (STB_LOCAL)
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
In kernel/auditsc.c (ffff8000101ef9b0)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffff8000101ef9b0-ffff8000101efa4c: audit_compare_gid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_compare_gid(kgid_t gid, struct audit_names *name, struct audit_field *f, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042eb00)
Location: kernel/auditsc.c:330
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
c042eb00-c042eb7c: audit_compare_gid (STB_LOCAL)
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
In kernel/auditsc.c (c000000000262660)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
c000000000262660-c000000000262754: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffe000163686)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffe000163686-ffffffe000163708: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81172e20)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81172e20-ffffffff81172e96: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81165fc0)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81165fc0-ffffffff81166036: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81170bf0)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff81170bf0-ffffffff81170c66: audit_compare_gid.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117e400)
Location: kernel/auditsc.c:330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
  - kernel/auditsc.c:audit_field_compare
```
**Symbols:**

```
ffffffff8117e400-ffffffff8117e476: audit_compare_gid.isra.0 (STB_LOCAL)
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

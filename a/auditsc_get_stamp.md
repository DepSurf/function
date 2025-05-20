# Function: <code>auditsc_get_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128d70)
Location: kernel/auditsc.c:1940
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff81128d70-ffffffff81128dda: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130f00)
Location: kernel/auditsc.c:1939
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff81130f00-ffffffff81130f6a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113ac70)
Location: kernel/auditsc.c:1944
Inline: False
```
**Symbols:**

```
ffffffff8113ac70-ffffffff8113acda: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c280)
Location: kernel/auditsc.c:1953
Inline: False
```
**Symbols:**

```
ffffffff8113c280-ffffffff8113c2eb: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149000)
Location: kernel/auditsc.c:1976
Inline: False
```
**Symbols:**

```
ffffffff81149000-ffffffff8114906b: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811579a0)
Location: kernel/auditsc.c:1983
Inline: False
```
**Symbols:**

```
ffffffff811579a0-ffffffff81157a0a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811649a0)
Location: kernel/auditsc.c:1969
Inline: False
```
**Symbols:**

```
ffffffff811649a0-ffffffff81164a0a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171680)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff81171680-ffffffff811716ea: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d500)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff8117d500-ffffffff8117d56a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190790)
Location: kernel/auditsc.c:2215
Inline: False
```
**Symbols:**

```
ffffffff81190790-ffffffff8119081f: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d9b0)
Location: kernel/auditsc.c:2232
Inline: False
```
**Symbols:**

```
ffffffff8118d9b0-ffffffff8118da3f: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e920)
Location: kernel/auditsc.c:2229
Inline: False
```
**Symbols:**

```
ffffffff8118e920-ffffffff8118e9af: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b7730)
Location: kernel/auditsc.c:2242
Inline: False
```
**Symbols:**

```
ffffffff811b7730-ffffffff811b77bf: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct audit_stamp *stamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea4e0)
Location: kernel/auditsc.c:2517
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff811ea4e0-ffffffff811ea55b: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct audit_stamp *stamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81230710)
Location: kernel/auditsc.c:2495
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff81230710-ffffffff8123078b: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct audit_stamp *stamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247280)
Location: kernel/auditsc.c:2494
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff81247280-ffffffff812472fb: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct audit_stamp *stamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812610f0)
Location: kernel/auditsc.c:2489
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff812610f0-ffffffff8126116b: auditsc_get_stamp (STB_GLOBAL)
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
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f23e8)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffff8000101f23e8-ffff8000101f246c: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432904)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
c0432904-c0432984: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266ba0)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
c000000000266ba0-c000000000266c78: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165af4)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffe000165af4-ffffffe000165b52: auditsc_get_stamp (STB_GLOBAL)
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
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175b20)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff81175b20-ffffffff81175b8a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168cc0)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff81168cc0-ffffffff81168d2a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811738f0)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff811738f0-ffffffff8117395a: auditsc_get_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int auditsc_get_stamp(struct audit_context *ctx, struct timespec64 *t, unsigned int *serial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811811b0)
Location: kernel/auditsc.c:2169
Inline: False
```
**Symbols:**

```
ffffffff811811b0-ffffffff8118121a: auditsc_get_stamp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *t</code> ➡️ <code>struct timespec64 *t</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct audit_stamp *stamp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec64 *t</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *serial</code>
</li>
</ul>
</details>
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

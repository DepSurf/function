# Function: <code>audit_field_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81126e09)
Location: kernel/auditsc.c:358
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_filter_rules
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
In kernel/auditsc.c (ffffffff8112f01b)
Location: kernel/auditsc.c:359
Inline: True
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
In kernel/auditsc.c (ffffffff81138cb5)
Location: kernel/auditsc.c:359
Inline: True
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
In kernel/auditsc.c (ffffffff8113a299)
Location: kernel/auditsc.c:360
Inline: True
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
In kernel/auditsc.c (ffffffff81146f5d)
Location: kernel/auditsc.c:360
Inline: True
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
In kernel/auditsc.c (ffffffff8115595a)
Location: kernel/auditsc.c:360
Inline: True
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
In kernel/auditsc.c (ffffffff81163145)
Location: kernel/auditsc.c:354
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116ea00)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff8116ea00-ffffffff8116ecb1: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117a880)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff8117a880-ffffffff8117ab31: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c990)
Location: kernel/auditsc.c:365
Inline: False
```
**Symbols:**

```
ffffffff8118c990-ffffffff8118cc1d: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81189b60)
Location: kernel/auditsc.c:381
Inline: False
```
**Symbols:**

```
ffffffff81189b60-ffffffff81189ded: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118ab60)
Location: kernel/auditsc.c:381
Inline: False
```
**Symbols:**

```
ffffffff8118ab60-ffffffff8118aded: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b3740)
Location: kernel/auditsc.c:387
Inline: False
```
**Symbols:**

```
ffffffff811b3740-ffffffff811b39cd: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e5c10)
Location: kernel/auditsc.c:377
Inline: False
```
**Symbols:**

```
ffffffff811e5c10-ffffffff811e5f6b: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122bcf0)
Location: kernel/auditsc.c:377
Inline: False
```
**Symbols:**

```
ffffffff8122bcf0-ffffffff8122c04b: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81242310)
Location: kernel/auditsc.c:378
Inline: False
```
**Symbols:**

```
ffffffff81242310-ffffffff8124267f: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125c120)
Location: kernel/auditsc.c:380
Inline: False
```
**Symbols:**

```
ffffffff8125c120-ffffffff8125c48f: audit_field_compare (STB_LOCAL)
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
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101efa50)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffff8000101efa50-ffff8000101efce8: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042eb7c)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
c042eb7c-c042ee04: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000262760)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
c000000000262760-c000000000262b58: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000163708)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffe000163708-ffffffe000163978: audit_field_compare (STB_LOCAL)
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
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81172ea0)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff81172ea0-ffffffff81173151: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81166040)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff81166040-ffffffff811662f1: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170c70)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff81170c70-ffffffff81170f21: audit_field_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct *tsk, const struct cred *cred, struct audit_field *f, struct audit_context *ctx, struct audit_names *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117e480)
Location: kernel/auditsc.c:354
Inline: False
```
**Symbols:**

```
ffffffff8117e480-ffffffff8117e731: audit_field_compare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>audit_log_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81122580)
Location: kernel/audit.c:1745
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81122580-ffffffff811228c8: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a4b0)
Location: kernel/audit.c:1756
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8112a4b0-ffffffff8112a7f8: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, const struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811341d0)
Location: kernel/audit.c:1895
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811341d0-ffffffff81134518: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, const struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811356e0)
Location: kernel/audit.c:2062
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811356e0-ffffffff811359cd: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, const struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81142420)
Location: kernel/audit.c:2070
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81142420-ffffffff8114270d: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, const struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150df0)
Location: kernel/audit.c:2123
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81150df0-ffffffff811510e5: audit_log_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_name(struct audit_context *context, struct audit_names *n, const struct path *path, int record_num, int *call_panic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115dab0)
Location: kernel/audit.c:2122
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8115dab0-ffffffff8115dd9d: audit_log_name (STB_GLOBAL)
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
In kernel/auditsc.c (ffffffff8116f180)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8116f180-ffffffff8116f474: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117b000)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8117b000-ffffffff8117b2f4: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8118dc00)
Location: kernel/auditsc.c:1313
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118dc00-ffffffff8118de6d: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8118ada0)
Location: kernel/auditsc.c:1331
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118ada0-ffffffff8118b01b: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8118b860)
Location: kernel/auditsc.c:1330
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118b860-ffffffff8118badb: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811b4490)
Location: kernel/auditsc.c:1339
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811b4490-ffffffff811b470b: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811e6a00)
Location: kernel/auditsc.c:1524
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811e6a00-ffffffff811e6cee: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8122cb50)
Location: kernel/auditsc.c:1502
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8122cb50-ffffffff8122ce3e: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81244be0)
Location: kernel/auditsc.c:1499
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81244be0-ffffffff81244f2c: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8125eb30)
Location: kernel/auditsc.c:1494
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8125eb30-ffffffff8125ee8e: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffff8000101f0ca0)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffff8000101f0ca0-ffff8000101f0fbc: audit_log_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (c04301e0)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c04301e0-c04304f0: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (c0000000002642e0)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c0000000002642e0-c0000000002646d8: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffe000164776)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffe000164776-ffffffe000164a48: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81173620)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81173620-ffffffff81173914: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811667c0)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811667c0-ffffffff81166ab4: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811713f0)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811713f0-ffffffff811716e4: audit_log_name.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117ec00)
Location: kernel/auditsc.c:1317
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8117ec00-ffffffff8117eef4: audit_log_name.constprop.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
</ul>

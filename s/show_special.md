# Function: <code>show_special</code>

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
In kernel/auditsc.c (ffffffff811261fd)
Location: kernel/auditsc.c:1171
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8112e6e7)
Location: kernel/auditsc.c:1170
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81138427)
Location: kernel/auditsc.c:1175
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8113996c)
Location: kernel/auditsc.c:1176
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff811466a5)
Location: kernel/auditsc.c:1176
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff811550bd)
Location: kernel/auditsc.c:1183
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81161c14)
Location: kernel/auditsc.c:1139
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116ed30)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8116ed30-ffffffff8116f179: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117abb0)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8117abb0-ffffffff8117aff9: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d810)
Location: kernel/auditsc.c:1193
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118d810-ffffffff8118dbf2: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118a9b0)
Location: kernel/auditsc.c:1211
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118a9b0-ffffffff8118ad92: show_special (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118bae0)
Location: kernel/auditsc.c:1210
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118bae0-ffffffff8118beb9: show_special.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811b4710)
Location: kernel/auditsc.c:1216
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811b4710-ffffffff811b4b06: show_special.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811e6cf0)
Location: kernel/auditsc.c:1386
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811e6cf0-ffffffff811e7284: show_special.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8122ce50)
Location: kernel/auditsc.c:1364
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8122ce50-ffffffff8122d3e4: show_special.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff812453c0)
Location: kernel/auditsc.c:1361
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff812453c0-ffffffff81245a79: show_special.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8125f320)
Location: kernel/auditsc.c:1362
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8125f320-ffffffff8125f9fa: show_special.isra.0 (STB_LOCAL)
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
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f0900)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffff8000101f0900-ffff8000101f0c9c: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042fde4)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c042fde4-c04301e0: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000263df0)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c000000000263df0-c0000000002642e0: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000164420)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffe000164420-ffffffe000164776: show_special (STB_LOCAL)
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
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811731d0)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811731d0-ffffffff81173619: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81166370)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81166370-ffffffff811667b9: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170fa0)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81170fa0-ffffffff811713e9: show_special (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_special(struct audit_context *context, int *call_panic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117e7b0)
Location: kernel/auditsc.c:1188
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8117e7b0-ffffffff8117ebf9: show_special (STB_LOCAL)
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
